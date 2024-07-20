---
permalink: /about/
classes: wide
title: "About"
---
I am deeply enthusiastic about expanding my knowledge base by exploring new subjects, honing my skills in basic and structured design, and delving into the intricacies of artificial intelligence (AI), deep learning, and machine learning. I am particularly interested in mastering these concepts using Python as well as other programming languages.

> 
- Familiar with Git and CI/CD 
- Played as a team member in agile
- Familiar with Git and CI/CD pipelines
- Good Experience with SQL/NoSQL databases such as Postgres as a SQL, Redis, Elastic-search


💎 Top skills:

| C# • ASP.NET Core • Git • Docker • Python • REST APIs • Redis • SQL • Algorithms • Data Structures • JSON |

<br>

# Projects 🎯

## 🕊️ Pigeon  <a href="https://github.com/abowfzl/Pigeon"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>

Pigeon is a monolotic clean architecture .Net dual-purpose project designed to help website owners monitor and manage the status of their web pages and aslo perform data mining to extract insights from news publisher websites.

### Features:

#### Part 1: Web Crawler and Monitoring
- Crawls websites to extract mentioned links on a page. [Link Crawler.cs](https://github.com/abowfzl/Pigeon/blob/master/Pigeon/Crawler/LinkCrawler.cs)
- Background job fetches and logs page response time and status code.
- Ticketing system for admins to assign crashed pages to team members and track resolutions (Admin interface).
- Login and user management with [Asp .Net Identity](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-8.0)

#### Part 2: Data Mining
- Extracts tags from news websites.
- the `Apriori` [algorithm](https://github.com/abowfzl/Pigeon/tree/master/Pigeon/Algoritms) implementation to find relationships between tags. check this page [DataMining.cs](https://github.com/abowfzl/Pigeon/blob/master/Pigeon/Pages/DataMining.cshtml.cs)

## <i class="fa fa-exchange" aria-hidden="true"></i> StexchangeClient.Net <a href="https://github.com/abowfzl/StexchangeClient"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>

StexchangeClient.Net is a base class library that wraps around the Stexchange APIs in C#. This library offers suitable methods with optional parameters for creating REST requests to Stexchange and raising different types of exceptions to handle a variety of scenarios.


`IStexchangeRestClient` is an interface that represents a functional method that you inject into your class and use in your services to make requests.

## 🐦 Sparrow  <a href="https://github.com/abowfzl/Sparrow.Api"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>

API With CQRS(MediatR) Pattern


- [Wrap](https://github.com/abowfzl/Sparrow.Api/tree/master/Sparrow.API/Results/Wrapping) the Api Response and handle [custom Exception](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.API/Exceptions/SparrowException.cs)
with [Exception Handling](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.API/Results/ExceptionHandling/GlobalExceptionFilter.cs)
or [unhandle exception](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.Services/Behaviours/UnhandledExceptionBehaviour.cs)

- Handle [Pagination](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.Core/PagedList.cs) Request and Response in this [folder](https://github.com/abowfzl/Sparrow.Api/tree/master/Sparrow.Core/Pagination)

- Also handle Paged List Async Query in [ToPagedListAsync](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.Data/Extentios/AsyncIQueryableExtensions.cs)


## <i class="fa fa-balance-scale" aria-hidden="true"></i> Balancer <a href="https://github.com/abowfzl/Balancer"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a> 

A `Clean Architecture` .NET Web API Application

This project is designed to provide a robust and maintainable solution for managing user accounts, transactions, configuration, background services, and unit tests using the Clean Architecture pattern.

This `.NET` web API application is built using the principles of `Clean Architecture`, which emphasizes separation of concerns, testability, and maintainability. It provides a flexible and scalable solution for managing user accounts, transactions, and configurations.

Managing user accounts and transactions is a common requirement for many applications. In this project, I focus on implementing functionalities to handle user account charges, including inserting, withdrawing, and injecting money transactions. Additionally, CRUD APIs are provided to manage accounts and configurations. A vital aspect of this project is ensuring the security and integrity of user data while maintaining a high level of performance.



## 🌩 TiTus  <a href="https://github.com/abowfzl/Titus"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>

A Console Application built with .Net 5 with 2 ClassLibrary (3 Layer (Core, Domain, Service)).


Repository Pattern For EF DbContext and Redis Wrapper in [Core](https://github.com/abowfzl/Titus/blob/master/Core) Layer,

Models In [Domain](https://github.com/abowfzl/Titus/blob/master/Core/Domain/),
Services and Distributed CacheManager Methods Implementation In [Service](https://github.com/abowfzl/Titus/blob/master/Service) Layer
Unit Tests with Moq Repository and Fake Services for Test Domain Services In [UnitTest](https://github.com/abowfzl/Titus/blob/master/Test)

### Usage
Read Huge Data From Ecxel Excel (like 500,000 Rows that are used in the Project) And Insert it into the Database.

Unit Test:
* [Moq]()
* [NUnit]()

> <i class="fa fa-code" aria-hidden="true"></i> <strong> Life Style Code: </strong>
<p align="center">
  <img src="/assets/images/abolfazl-life-style.png" alt="Abolfazl Moslemian Life Style"/>
</p>


> <i class="fab fa fa-github" aria-hidden="true"></i> <strong> Github Stats: </strong>
<p align="center">
 <a href="https://github.com/abowfzl" alt="Abolfazl Moslemian's github stats">
  <img src="https://github-readme-stats.vercel.app/api?username=Abowfzl&theme=tokyonight&show_icons=true" alt="Github Stats"/>
 </a>
</p>

> <i class="fab fa-fw fa-stack-overflow" aria-hidden="true"></i> <strong> Stack Overflow Stats: </strong>
<p align="center">
 <a href="https://stackoverflow.com/users/17593676/abolfazl-moslemian" alt="Abolfazl Moslemian's Stack Overflow stats">
    <img src="https://so-stats-kurt-liao.vercel.app/api?user=17593676&cache=true" alt="Stack Overflow Stats" />
  </a>
</p>


<br/>
<p align="center">
  👯 Get in touch me at: 
  <a href="https://twitter.com/abowfzl"><i class="fab fa-fw fa-twitter-square" aria-hidden="true"></i><span class="label">Twitter</span></a>
  <a href="https://linkedin.com/in/abowfzl"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i><span class="label">LinkedIn</span></a>
  <a href="mailto:abowfzl@gmail.com"><i class="fas fa-fw fa-envelope-square" aria-hidden="true"></i><span class="label">Email</span></a>
</p>