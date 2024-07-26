# .NET programming learning roadmap

>Introducing the basic .NET programming learning path step by step. This roadmap is compiled based on dotnet document. Refer to [dotnet documentation](https://learn.microsoft.com/en-us/docs/).

You can also use some IDEs that have a built-in .NET running environment such as `Visual Studio`, `Visual Studio for Mac` or `Jetbrains Rider`...

## What is .NET?

**.NET is an open source developer platform, created by Microsoft, for building many different types of applications.**

### .NET

.NET is a free, cross-platform, open source developer platform for building many different types of applications.

With .NET, you can use multiple languages, editors, and libraries to build for web, mobile, desktop, games, IoT, and more.

### Languages

You can write .NET apps in C#, F#, or Visual Basic.

- C# is a simple, modern, object-oriented, and type-safe programming language.
- F# is a programming language that makes it easy to write succinct, robust, and performant code.
- Visual Basic is an approachable language with a simple syntax for building type-safe, object-oriented apps.

### Cross Platform

Whether you're working in C#, F#, or Visual Basic, your code will run natively on any compatible operating system. You can build many types of apps with .NET. Some are cross-platform, and some target a specific set of operating systems and devices.

### One consistent API

.NET provides a standard set of base class libraries and APIs that are common to all .NET applications.

Each app model can also expose additional APIs that are specific to the operating systems it runs on, or the capabilities it provides. For example, ASP.NET is the cross-platform web framework that provides additional APIs for building web apps that run on Linux or Windows.

### Libraries

To extend functionality, Microsoft and others maintain a healthy .NET package ecosystem.

[NuGet](https://www.nuget.org/) is a package manager built specifically for .NET that contains over 100,000 packages.

## Prerequisites

- Basic knowledge of data structures and algorithms
- Basic knowledge of object-oriented programming (OOP)
- Basic knowledge of c# language
- Basic knowledge of html, css, javascript
- Basic knowledge of databases

## Concepts

- Design Pattern: MVC (View-Model-Controller), MVVM (Model-View-ViewModel),...
- API (Application Programming Interface)
- ORM (Object Relational Mapping): Entity Framework, Entity Framework Core,...
- HTTP and HTTPS
- HTTP response status codes
- [**Common C# code conventions**](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) and [**SQL Server Coding Standards**](https://github.com/CA-CST-SII/Software-Standards/blob/master/SQL%20Server%20Coding%20Standards.md)

## Roadmap

### Basic

- **[Part 1: Install .NET and SQL Server environment in Visual Studio Code](https://github.com/NguyenPhuDuc307/install-dotnet-sql-server)**

  >Instructions for installing the .NET application development environment on Visual Studio Code and using Microsoft SQL Server database. SQL Server will be installed running on Docker. You can use this guide to do it on **Windows**, **MacOS**.

- **[Part 2: Get started with ASP.NET Core MVC, Connect to SQL Server database to CRUD](https://github.com/NguyenPhuDuc307/get-started-dotnet-mvc)**
  >This tutorial teaches ASP.NET Core MVC web development with models, controllers, and views. Initialize an MVC app and connect to SQL Server database to CRUD.

- **[Part 3: Add a new field and add validation to an ASP.NET Core MVC application](https://github.com/NguyenPhuDuc307/add-field-and-validation)**
  >This tutorial teaches how to add new fields to entities and migrate them into the database. Then we will learn how to validate properties using `ValidationAttribute`.

- **[Part 4: Seed the database an ASP.NET Core MVC application](https://github.com/NguyenPhuDuc307/seed-the-database)**
  >This tutorial teaches how to seed the database, create a new class named `DbInitializer` in the Models folder. If there are any records in the database, the seed initializer returns and no records are added.

- **[Part 5: Use AutoMapper in MVVM Pattern ASP.NET Core](https://github.com/NguyenPhuDuc307/mvvm-design-pattern)**
  >ASP.Net Core has a wide array of libraries that provide great assistance in development strategy. Using MVVM pattern and AutoMapper you can reduce your code lines and produce more reusable and efficient code.

- **[Part 6: Use dependency injection in .NET](https://github.com/NguyenPhuDuc307/dependency-injection)**
  >.NET supports the dependency injection (DI) software design pattern, which is a technique for achieving [Inversion of Control (IoC)](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles#dependency-inversion) between classes and their dependencies. Dependency injection in .NET is a built-in part of the framework, along with configuration, logging, and the options pattern.
  
- **[Part 7: Add search, sorting, pagination to ASP.NET Core MVC application](https://github.com/NguyenPhuDuc307/search-sorting-pagination)**
  >This tutorial teaches how to add search, sorting, pagination to ASP.NET Core MVC application.

- **[Part 8: Introduction to relationships](https://github.com/NguyenPhuDuc307/introduction-relationship)**
  >This document provides a simple introduction to the representation of relationships in object models and relational databases, including how EF Core maps between the two.

- **[Part 9: File Storage in .NET](https://github.com/NguyenPhuDuc307/file-storage)**
  >This tutorial shows how to store and manage files in an ASP.NET Core MVC application.

- **[Part 10: Create a web API with ASP.NET Core](https://github.com/NguyenPhuDuc307/web-api)**
  >This tutorial teaches the basics of building a controller-based web API that uses a database. Another approach to creating APIs in ASP.NET Core is to create minimal APIs. For help in choosing between minimal APIs and controller-based APIs. For a tutorial on creating a minimal API, see [Tutorial: Create a minimal API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio).

- **[Part 11: Add Identity on ASP.NET Core](https://github.com/NguyenPhuDuc307/add-identity)**
  >Users can create an account with the login information stored in Identity or they can use an external login provider. Supported external login providers include Facebook, Google, Microsoft Account, and Twitter.

- **[Part 12: Authentication JWT API with Identity](https://github.com/NguyenPhuDuc307/auth-jwt)**
  >The HttpClient class is used to send HTTP requests (Http Request Message - Request) and receive Response responses (Http Response Message) from those queries. This class belongs to the System.Net.Http namespace, this namespace contains classes that help create communication between client and server.

- **[Part 13: Add Authorization header for Swagger](https://github.com/NguyenPhuDuc307/auth-swagger)**
  >**Bearer authentication** (also called **token authentication**) is an [HTTP authentication scheme](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication) that involves security tokens called bearer tokens. The name “Bearer authentication” can be understood as “give access to the bearer of this token”. The bearer token is a cryptic string, usually generated by the server in response to a login request.

### Advanced

- **Distributed caching in ASP.NET Core**
  >A distributed cache is a cache shared by multiple app servers, typically maintained as an external service to the app servers that access it. A distributed cache can improve the performance and scalability of an ASP.NET Core app, especially when the app is hosted by a cloud service or a server farm.

- **AJAX JQuery with ASP.NET Core**
  >This tutorial teaches a short course that helps you create an add, edit, delete pagination search screen using ASP.NET MVC and JQuery AJAX for key operations.
  
- **Unit test controller logic in ASP.NET Core**
  >Unit tests involve testing a part of an app in isolation from its infrastructure and dependencies. When unit testing controller logic, only the contents of a single action are tested, not the behavior of its dependencies or of the framework itself.

- **Get started with ASP.NET Core SignalR**
  >ASP.NET Core SignalR is an open-source library that simplifies adding real-time web functionality to apps. Real-time web functionality enables server-side code to push content to clients instantly.
  
Next let's [Part 1: Install .NET and SQL Server environment in Visual Studio Code](https://github.com/NguyenPhuDuc307/install-dotnet-sql-server).
