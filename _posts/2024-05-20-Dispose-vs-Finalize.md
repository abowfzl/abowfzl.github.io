---
classes: wide
title:  "Dispose vs Finalize"
categories: CSharp
header:
  teaser: /assets/images/finalize-dispose.png
author: Abolfazl Moslemian
tags:
  - CSharp-Dispose
  - CSharp-Finalize
  - CSharp 
---

> Dispose Method in C#

The Dispose method serves a crucial purpose: to free unmanaged resources the Garbage Collector can't handle itself. Simply put, it's like a memory emancipator, liberating `trapped` memory spaces!
{: .notice--info}

```
public class DisposeExample : IDisposable
{
    bool disposed = false;

    // Declare your Filestream object.
    private FileStream fileStream = null;

    // Implement dispose.
    public void Dispose()
    {
        Dispose(true);
        GC.SuppressFinalize(this);
    }

    protected virtual void Dispose(bool disposing)
    {
        if (!disposed)
        {
            if (disposing)
            {
                fileStream?.Dispose();
            }

            disposed = true; 
        }
    }
}
```

## The Finalize Method Basics

In simple terms, Finalize method is a destructor provided by Microsoft's `Object` class, a method that helps to tidy up a mess after a function party, specifically focusing on cleaning up unmanaged resources.

Consider the following example:

```
class FinalizeExample
{
    FileStream fileStream;

    // Constructor, opens a file named "temp.dat"
    public FinalizeExample()
    {
        fileStream = new FileStream("temp.dat", FileMode.Create);
    }

    // destructor
    ~FinalizeExample()
    {
        // File closing statement
        fileStream.Close();
    }
}
```
In this FinalizeExample class, we have an unmanaged resource nativeResource. The destructor, marked with a tilde (~), frees this unmanaged resource during finalization.

## Dispose vs Finalize

The Dispose method, when called, immediately frees up resources, both managed and unmanaged. This bolsters the performance of your code since it relieves resources from further use, like giving your computer a power nap, so it's ready to take on the next task.
On the other hand:
The Finalize, it is automatic and works during the GC process, but it's laser-focused on resources that Dispose can't touch. It's like having a house cleaner who, after cleaning your house today, shows up unannounced next week just to double-check everything is in order!