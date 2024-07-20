---
classes: wide
title:  "HashSet in C# with Examples"
categories: CSharp
header:
  teaser: /assets/images/hash-set.png
author: Abolfazl Moslemian
tags:
  - CSharp-Generic-HashSet
  - CSharp 
---

In C#, HashSet is an unordered collection of unique elements. This collection is introduced in .NET 3.5. It provides fast lookups and high-performance set operations  and uses the hash table for storage. This collection is of the generic type collection and it is  part of the `System.Collections.Generic` namespace. It is generally used when we want to prevent duplicate elements from being placed in the collection. The performance of the HashSet is much better in comparison to the list. 

**Important Points Related To HashSet in C#**

- The HashSet class implements the ICollection, IEnumerable, IReadOnlyCollection, ISet, IEnumerable, IDeserializationCallback, and ISerializable interfaces.
- In HashSet, the order of the element is not defined. You cannot sort the elements of HashSet.
- HashSet elements are always unique. In oder word, duplicate elements are not allowed
- It provides many mathematical set operations, such as intersection, union, and difference.
- A HashSet is a dynamic collection means the size of the HashSet is automatically increased when the new elements are added.
- In HashSet, you can only store the same type of elements.

**Example:**

```
// C# program to illustrate how to create hashset
using System;
using System.Collections.Generic;

class HashsetTest {

	// Main Method
	static public void Main()
	{

		// Creating HashSet
		HashSet<string> myhash1 = new ();

		// Add the elements in HashSet
		myhash1.Add("C");
		myhash1.Add("C++");
		myhash1.Add("C#");
		myhash1.Add("Java");
		myhash1.Add("Ruby");
		Console.WriteLine("Elements of myhash1:");

		// Accessing elements of HashSet
		foreach(var val in myhash1)
		{
			Console.WriteLine(val);
		}

		// Creating another HashSet
		// using collection initializer to initialize HashSet
		HashSet<int> myhash2 = new () 
        {   10,
		    100,
            1000,
            10000,
            100000
        };
				
		// Display elements of myhash2
		Console.WriteLine("Elements of myhash2:");
		foreach(var value in myhash2)
		{
			Console.WriteLine(value);
		}
	}
}
```