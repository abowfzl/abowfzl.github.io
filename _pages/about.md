---
permalink: /about/
classes: wide
layout: splash
title: "About"
---

### Abolfazl Moslemian  
**Software Developer | ML & Data Science Specialist**

<small>Abolfazl Moslemian is a passionate innovator in the world of software development and machine learning. With a sharp focus on AI, deep learning, and neural networks, he pushes the boundaries of technology to create next-generation, cloud-based solutions using the .Net platform. With a vision to drive the future of AI and software development, Abolfazl is not just keeping up with the latest technological trends—he’s setting them. **Abolfazl's goal is clear: to revolutionize industries through the intelligent application of machine learning and AI-powered tools.**</small>

## Latest Work: Travel Adviser Project 🚀
<small>In his latest groundbreaking work on the **Travel Adviser project**, Abolfazl is pioneering personalized vacation planning by harnessing the power of advanced AI models like GPT4All and LangChain. By integrating natural language processing and Neo4j's graph-based insights, his project transforms travel data into smart, tailor-made recommendations for every type of traveler.</small>

## Academic Excellence 🎓

<small>Abolfazl’s academic journey at **Qom University**, where he ranked among the top 10% of his class, has fueled his hunger for cutting-edge research. Notably, he ranked in the **top 0.5%** of students nationwide for the Iran National University entrance exam, competing with over 200,000 students.</small>

## Research Experience 🔬

<small>As a member of the **Smart Software Lab** at Qom University, Abolfazl has been developing machine learning algorithms for personalized travel planning and exploring AI applications in natural language processing and data analysis. This hands-on research prepares him for advanced roles in AI and deep learning applications.</small>

## Key Projects 💡

- <small>**Pigeon**: A monolithic, clean architecture .Net project designed to help website owners monitor and manage the status of their web pages while performing data mining to extract insights from news publisher websites.</small> 
    - <small>Key Features:</small> 
        - <small>Web crawling and monitoring for real-time status of web pages.</small>
        - <small>Implements Apriori algorithm for data mining insights.</small>
        - <small>Admin interface for tracking website issues and solutions.</small>

- <small>**Balancer**: A .Net web API application built using Clean Architecture, focusing on user management, transactions, and configurations.</small>
    - <small>Key Features:</small>
        - <small>Manages user accounts and transactions with secure CRUD operations.</small>
        - <small>Ensures data security while maintaining performance.</small>

- <small>**Sparrow**: An API project implementing the CQRS (MediatR) pattern to decouple command and query databases, improving application performance and scalability.</small>
    - <small>Key Features:</small>
        - <small>Wraps API responses with a unified handling system for errors and pagination.</small>
        - <small>Implements behavior for unhandled exceptions and async query handling.</small>

- <small>**EpicPic**: A face recognition system using convolutional neural networks with an impressive 97.38% accuracy for student and staff identification.</small>

- <small>**Travel Adviser**: A chatbot for personalized travel planning, leveraging AI technologies like ChatGPT, LangChain, and Neo4j.</small>

## Certifications 📜
- <small>**Machine Learning** (Stanford University, Coursera): Completed with a grade of 92.65%</small>
- <small>**Python for Data Science, AI & Development** (IBM, Coursera): Completed with a grade of 94.91%</small>

## Professional Expertise 🌐
<small>Abolfazl's professional achievements include key roles at **Exbito** and **Mootantroo**, where he led projects in API development, infrastructure monitoring, and performance optimization. His approach to software development emphasizes clean, scalable architecture, setting new standards for efficiency and innovation.</small>

## Skills and Technologies 💻
<small>From optimizing financial transactions to building high-performance web APIs, Abolfazl is always looking to push the envelope. His expertise spans **Python**, **.Net Core**, **TensorFlow**, **PyTorch**, **SQL Server**, **Redis**, and various other tools, making him a versatile problem-solver across multiple domains.</small>

---

> 
💎 **Top skills**:

| C# • ASP.NET Core • Git • Docker • Python • REST APIs • Redis • SQL • Algorithms • Data Structures • JSON • Nginx |

<br>

# Projects 🎯

## 🧳 Travel Adviser <a href="https://github.com/abowfzl/Travel-Adviser"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>
<small>Travel Adviser is an intelligent vacation planning application that uses GPT4All, OpenAI, LangChain, and Neo4j to provide personalized travel recommendations and itineraries. It features an interactive user interface and a scalable architecture, utilizing machine learning and AI models to enhance user experience with real-time travel data analysis.</small>

### Key Features:
- <small>**Personalized travel suggestions** powered by advanced AI models.</small>
- <small>**User-friendly interface** for exploring travel options.</small>
- <small>**Scalable microservices architecture** for seamless deployment.</small>

## 🕊️ Pigeon  <a href="https://github.com/abowfzl/Pigeon"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>
<small>Pigeon is a monolithic clean architecture .Net project designed to help website owners monitor and manage the status of their web pages and also perform data mining to extract insights from news publisher websites.</small>

### Key Features:

#### Part 1: Web Crawler and Monitoring
- <small>Crawls websites to extract mentioned links on a page. [Link Crawler.cs](https://github.com/abowfzl/Pigeon/blob/master/Pigeon/Crawler/LinkCrawler.cs)</small>
- <small>Background job fetches and logs page response time and status code.</small>
- <small>Ticketing system for admins to assign crashed pages to team members and track resolutions (Admin interface).</small>
- <small>Login and user management with [Asp .Net Identity](https://learn.microsoft.com/en-us/aspnet/identity/overview/getting-started/introduction-to-aspnet-identity)</small>

#### Part 2: Data Mining
- <small>Extracts tags from news websites.</small>
- <small>Implements the `Apriori` [algorithm](https://github.com/abowfzl/Pigeon/tree/master/Pigeon/Algoritms) to find relationships between tags. Check this page [DataMining.cs](https://github.com/abowfzl/Pigeon/blob/master/Pigeon/Pages/DataMining.cshtml.cs)</small>

## 🔁 StexchangeClient.Net <a href="https://github.com/abowfzl/StexchangeClient"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>

<small>StexchangeClient.Net is a base class library that wraps around the Stexchange APIs in C#. This library offers suitable methods with optional parameters for creating REST requests to Stexchange and raising different types of exceptions to handle a variety of scenarios.</small>

<small>`IStexchangeRestClient` is an interface that represents a functional method that you inject into your class and use in your services to make requests</small>

## 🐦 Sparrow  <a href="https://github.com/abowfzl/Sparrow.Api"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>
<small>
API With CQRS (MediatR) Pattern
</small>
- <small>[Wrap](https://github.com/abowfzl/Sparrow.Api/tree/master/Sparrow.API/Results/Wrapping) the API response and handle [custom exceptions](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.API/Exceptions/SparrowException.cs) with [exception handling](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.API/Results/ExceptionHandling/GlobalExceptionFilter.cs).</small>
- <small>Handles [pagination](https://github.com/abowfzl/Sparrow.Api/blob/master/Sparrow.Core/PagedList.cs) requests with async query handling.</small>

## ⚖️ Balancer <a href="https://github.com/abowfzl/Balancer"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a> 
<small>
A Clean Architecture .NET Web API Application.
</small>
<small>
This project provides a robust and maintainable solution for managing user accounts, transactions, and configurations using the Clean Architecture pattern.
</small>

## 🌩 TiTus  <a href="https://github.com/abowfzl/Titus"> <i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">Link</span></a>
<small>
A Console Application built with .Net 5 using a 3-layer architecture (Core, Domain, Service).
</small>

### Key Features:
- <small>Repository pattern for EF DbContext and Redis wrapper in [Core Layer](https://github.com/abowfzl/Titus/blob/master/Core).</small>
- <small>Distributed CacheManager implementation in the Service layer.</small>
- <small>Unit tests using Moq and NUnit.</small>

---

> <i class="fa fa-code" aria-hidden="true"></i> **Life Style Code:** 

<p align="center">
  <img src="/assets/images/abolfazl-life-style.png" alt="Abolfazl Moslemian Life Style"/>
</p>

> <i class="fab fa-fw fa-github" aria-hidden="true"></i> **Github Stats:** 

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

---

<p align="center">
  😊 Get in touch me at: 
  <a href="https://twitter.com/abowfzl"><i class="fab fa-fw fa-twitter-square" aria-hidden="true"></i><span class="label">Twitter</span></a>
  <a href="https://linkedin.com/in/abowfzl"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i><span class="label">LinkedIn</span></a>
  <a href="mailto:abowfzl@gmail.com"><i class="fas fa-fw fa-envelope-square" aria-hidden="true"></i><span class="label">Email</span></a>
</p>
