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

## Roadmap

### Basic

- **Get started with ASP.NET Core**
  >This tutorial teaches ASP.NET Core MVC web development with models, controllers, and views. Initialize an MVC app and connect to SQL Server database to CRUD.

- **Add a new field and add validation to an ASP.NET Core MVC application**
  >This tutorial teaches how to add new fields to entities and migrate them into the database. Then we will learn how to validate properties using `ValidationAttribute`.

- **Seed the database an ASP.NET Core MVC application**
  >This tutorial teaches how to seed the database, create a new class named `SeedData` in the Models folder. If there are any records in the database, the seed initializer returns and no records are added.

- **Add search, sorting, pagination to ASP.NET Core MVC application**
  >This tutorial teaches how to add search, sorting, pagination to ASP.NET Core MVC application.

- **Use dependency injection in .NET**
  >.NET supports the dependency injection (DI) software design pattern, which is a technique for achieving [Inversion of Control (IoC)](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles#dependency-inversion) between classes and their dependencies. Dependency injection in .NET is a built-in part of the framework, along with configuration, logging, and the options pattern.

- **Introduction to relationships**
  >This document provides a simple introduction to the representation of relationships in object models and relational databases, including how EF Core maps between the two.

- **File Storage in .NET**
  >This tutorial shows how to store and manage files in an ASP.NET Core MVC application.

- **Create a web API with ASP.NET Core**
  >This tutorial teaches the basics of building a controller-based web API that uses a database. Another approach to creating APIs in ASP.NET Core is to create minimal APIs. For help in choosing between minimal APIs and controller-based APIs. For a tutorial on creating a minimal API, see [Tutorial: Create a minimal API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio).

### Advanced

- **Introduction to Identity on ASP.NET Core**
  >Users can create an account with the login information stored in Identity or they can use an external login provider. Supported external login providers include Facebook, Google, Microsoft Account, and Twitter.

- **JWT Token Creation, Authentication And Authorization In ASP.NET Core**
  >In this article, I will explain how to create the JWT token and how to Authenticate and Authorize it in very simple steps.

- **Distributed caching in ASP.NET Core**
  >A distributed cache is a cache shared by multiple app servers, typically maintained as an external service to the app servers that access it. A distributed cache can improve the performance and scalability of an ASP.NET Core app, especially when the app is hosted by a cloud service or a server farm.

- **Unit test controller logic in ASP.NET Core**
  >Unit tests involve testing a part of an app in isolation from its infrastructure and dependencies. When unit testing controller logic, only the contents of a single action are tested, not the behavior of its dependencies or of the framework itself.

- **Get started with ASP.NET Core SignalR**
  >ASP.NET Core SignalR is an open-source library that simplifies adding real-time web functionality to apps. Real-time web functionality enables server-side code to push content to clients instantly.
  
Next let's [Install .NET and SQL Server environment in Visual Studio Code](https://github.com/NguyenPhuDuc307/install-dotnet-sql-server).
