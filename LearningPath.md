# ASP.NET CORE SYLLABUS MODIFIED
`ASP.NET Core Authors: Scott Allen, Gill Cleeren, Eric Fisher, Shawn Wildermuth, Steve Gordon, Erik Dahl, Alex Wolf, Roland Guijt, Peter Kellner, Rag Dhiman`

`ASP.NET Core is Microsoft's modern, cross-platform framework for building web applications and web APIs. In this path, you will learn everything you need to know about building ASP.NET Core applications, from building web applications with Razor to creating APIs.`

## RELATED TOPICS
- C#
- HTML 
- .NET
- web developer
- Entity Framework Core

# What you will learn
- Creating applications with Razor Pages
- Creating applications using the MVC Framework
- Building APIs with ASP.NET Core
- Using ASP.NET Core's built-in dependency injection framework
- Creating reusable components using Tag Helpers
- How to secure your ASP.NET Core applications
- Different authentication strategies available for your application
- Using SignalR to build real-time communication into your apps

# Pre-requisites
`Basic web development skills and familiarity with the C# language`

# BEGINNER LEARNING PATH
`Take your understanding of ASP.NET Core to the next level with the courses in this section by doing a deep dive on ASP.NET Core's built-in dependency injection framework, how the ASP.NET Core request lifecycle works and the extension points available to you for an MVC application.`

 # 1. ASP.NET Core Fundamentals By Scott Allen
`This course shows you all the features you'll need to build your first application with ASP.NET Core.`

## Description
`ASP.NET Core is the latest web framework from Microsoft, and is engineered to be fast, easy, and work across platforms. In this course, ASP.NET Core Fundamentals, you will build your first application with ASP.NET Core from scratch. First, you will learn how to work with a database to display and edit data. Then, you will explore middleware, view components, and database migrations with the Entity Framework. Finally, you will delve into building an API controller, and see how to work with client-side libraries. By the end of this course, you will have the skills and knowledge of ASP.NET Core needed to be productive in a typical business-oriented application.`

# Course FAQ

---
# What is ASP.NET Core?
`ASP.NET Core is a free, open-source web framework from Microsoft that offers high performance and cross-platform functonality for building web apps and services, mobile backends, and more.`

# What are the advantages of ASP.NET Core?
` Some benefits of ASP.NET Core include:`
- It is an open-source framework
- Easy to build cross-platform web apps
- It requires less coding, meaning easier maintenance
- High performance
- Easily testable

# Who is this course for?
`Any and everyone who wants to learn ASP.NET Core to build high-performing, cross-platform applications.`

# What will I learn in this course?
`This course will teach you the basics of ASP.NET Core, including:`
- How to build an application with ASP.NET Core
- How to work with a database
- Entity Framework
- Middleware
- View components
- Database migrations
- How to build an API controller
- Client-side libraries
- Much more

# Are there prerequisites to this course?
`Before diving into ASP.NET Core, you should be comfortable with C# programming, HTML, and have some general experience at web programming.`

# Scott Allen
`About the author
Scott has over 15 years of experience in commercial software development and is a frequent speaker at national conferences, and local user groups. Scott is a Microsoft MVP and has authored books on several Microsoft technologies, including ASP.NET, C#, and Windows Workflow.`

# Course Overview
`Hi. This is Scott Allen, and this is my ASP.NET Core Fundamentals course. ASP.NET Core is the latest web framework from Microsoft, and it's engineered to be fast, easy, and work across platforms. In this course, we'll build an application from scratch and see how to work with ASP.NET and databases to build a website of restaurant information. During the course, you'll learn about Razor Pages and API controllers. We'll be using the Entity Framework and create and execute Entity Framework migrations. We'll also see how to integrate client‑side libraries into ASP.NET Core and learn some of the behind‑the‑scenes internals. Along the way, you might even hear a story about my childhood. By the end of the course, you'll be ready to build your own applications using ASP.NET Core. But before we begin, make sure you're comfortable with the C# language, HTML, and have some general experience at web programming.`

# Course Overview
- Course Overview1m
- Overview of the 3.0 Upgrade2m

# Drilling into Data
- Introduction0m
- Creating the New Project3m
- Editing Razor Pages4m
- Adding a Razor Page3m
- Using the Scaffolding Tools3m
- Injecting and Using Configuration4m
- Creating an Entity3m
- Building a Data Access Service4m
- Registering a Data Service3m
- Building a Page Model1m
- Displaying a Table of Restaurants2m
- Summary1m

# Working with Models and Model Binding
- Introduction0m
- Working with HTML Forms3m
- Building a Search Form2m
- Finding Restaurants by Name2m
- Binding to a Query String5m
- Using Model Binding and Tag Helpers5m
- Building a Detail Page4m
- Linking to the Details7m
- Specifying Page Routes4m
- Fetching Restaurants by ID2m
- Handling Bad Requests4m
- Summary0m

# Editing Data with Razor Pages
- Introduction0m
- Creating the Restaurant Edit Page4m
- Building an Edit Form with Tag Helpers9m
- Model Binding an HTTP POST Operation6m
- Adding Validation Checks4m
- Using Model State and Showing Validation Errors5m
- Following the POST-GET-REDIRECT Pattern4m
- Building a Create Restaurant Page3m
- Adding Create to the Data Access Service2m
- Handling Create vs. Update Logic3m
- Confirming the Last Operation5m
- Summary0m

# Working with SQL Server and the Entity Framework Core
- Introduction0m
- Installing the Entity Framework3m
- Implementing an Entity Framework DbContext2m
- Using the Entity Framework Tools4m
- Using Other Databases and Tools3m
- Adding Connection Strings and Registering Services6m
- Adding Database Migrations6m
- Running Database Migrations3m
- Implementing a Data Access Service2m
- Saving and Commiting Data7m
- Modifying the Service Registration2m
- Summary0m

# Building the User Interface
- Introduction0m
- Using Razor Layout Pages and Sections6m
- Implementing a Delete Restaurant Page Model5m
- Implementing the Delete Markup3m
- Using _ViewImports and _ViewStart Files5m
- Reusing Markup with Partial Views5m
- Rendering Partial Views3m
- Implementing a ViewComponent8m
- Rendering a ViewComponent5m
- Scaffolding a Complete Set of CRUD Pages3m
- Summary0m

# Integrating Client-side JavaScript and CSS
- Introduction1m
- Serving Static Files and Content from wwwroot4m
- Using ASP.NET Core Environments5m
- Enforcing Validation on the Client6m
- Loading Restaurants from the Client4m
- Implementing an API Controller6m
- Using DataTables6m
- Managing Client Libraries Using npm and NodeJS8m
- Managing Production Scripts and Development Scripts4m
- Serving Files from the node_modules Directory5m
- Creating Sortable, Searchable Data Grids with DataTables5m
- Summary1m

> # Working with the Internals of ASP.NET Core
- Introduction1m
- Exploring the Application Entry Point6m
- Processing Summer Corn with the Allen Family6m
- Exploring the Application Middleware7m
- Building Custom Middleware8m
- Logging Application Messages5m
- Configuring the App Using the Default Web Host Builder6m
- Summary1m

> # Deploying ASP.NET Core Web Applications
- Introduction1m
- Publishing Apps vs. Deploying Apps4m
- Using dotnet publish5m
- Using MSBuld to Execute npm install5m
- Building Self-contained Applications5m
- Deploying to a Web Server7m
- Exploring web.config and How IIS Hosting Works5m
- Setting up Automatic Entity Framework Migrations8m
- Connecting to a SQL Server Database7m
- Conclusion0m

---
# 2. Building Web Applications with ASP.NET Core MVC By Gill Cleeren
`In this course, you'll learn how to build a complete application with ASP.NET Core 3.0/5.0 MVC using Visual Studio 2019 in a practical, hands-on way.`

# Course info
# Rating (400 Star)
* LevelBeginner 
* UpdatedDec 14, 2020 
* Duration4h 24m 

# Description
`ASP.NET Core 3.0 and ASP.NET Core 5.0 contain many new features allowing developers to more easily build apps with ASP.NET Core MVC. In this course, Building Web Applications with ASP.NET Core MVC, you'll learn how to build a fully working modern web application using ASP.NET Core 3/5 MVC. First, you'll learn how an ASP.NET Core MVC project is configured. Next, you'll find out how to build several pages that connect with a database using Entity Framework Core. To build these pages, you'll learn about Razor, tag helpers, layouts and view components. Finally, you'll understand how to authenticate users using ASP.NET Identity. When you're finished with this course, you'll have the skills and knowledge of ASP.NET Core MVC to build real-world web applications. This course is updated to be compatible with .NET 5.0.`


# Gill Cleeren
# About the author
`Gill Cleeren is a Microsoft Regional Director, MVP and Pluralsight author. Gill is a freelance solution architect living in Belgium. He focuses on web and mobile development and loves Xamarin. He's also a frequent speaker at many international conferences. Gill also founded Techorama, the biggest IT conference in Belgium and the Netherlands. You can find his website at www.snowball.be.`

# Section Introduction Transcripts
# Course Overview
`[Autogenerated] Hi, everyone. My name is Jill Clearing and welcome to my goals. Building web applications with a Speedo net core MVC I'm the CEO of Experience Belgium and help customers with web and mobile application development are Pluralsight Court MVC is the preferred way off building maintainable and testable rip applications where the .NET cross-platform way back in 2016, Microsoft launched a spirited core and .NET core as the future off ESP, internet and .NET. Since then, quite a few updates have been released are Pluralsight Core is now already at version five, which was launched in November 2020. Microsoft has extended the platform already quite a lot, and it will keep adding more and more features in .NET core and a spirited core. Going forward discourse is aimed at giving you a hand zone way to learn about a spirited Cory MVC. You'll build together with me a full application in Visual Studio 2019. You'll see how to apply the MVC pattern. Built views work with the database and much more in the course. Dinners were using ESP internet core S3, but the schools is now fully updated to be compatible, also with a spirit of 45 Some of the major topics that we will cover include built a fully working application starting from file new project that you can use as the foundation for your own project. Understand the architectural, often a spirited core application. Learn about the new features in a spirited core MVC. Such a stack helpers and view components Access data in a database using Entity Framework Court include a Pluralsight identity to allow users to authenticate to the site. By the end of the course, you'll know how you can build a full real world application using a speeder. Net core MVC envisions 2D, 2019 before beginning to schools. You should be familiar with some tea job and HTML. I hope you will join me on this journey to learn a spirited code MVC with the building web applications with a Spirit Court MVC course here at Pluralsight`

# Table of Contents (Notes)

# 1. Course Overview
> Module length:2m 23s

# 2. Course Introduction
`Module length:18m 52s (completed)`
* Module Introduction
1m 54s
* What Will You Learn from This Course?
4m 30s
* Demo: Looking at the Finished Application
1m 36s
* What Is ASP.NET Core?
7m 11s
* Getting Your Machine Ready
1m 17s
* Demo: Getting Your Machine Ready
1m 27s
* Summary
0m 54s

# 3. Setting up an MVC Application
`Module length:25m 58s`
* Module Introduction
1m 1s
* Exploring the Project Structure
2m 5s
* Demo: Exploring the Project Structure
3m 12s
* Site Configuration
10m 49s
* Demo: Site Configuration
7m 56s
* Summary
0m 52s

# 4. Creating the List Page
`Module length:55m 29s`
* Module Introduction
2m 18s
* Demo: Looking at the Final Page
0m 30s
* Hello MVC
2m 46s
* Creating the Model and the Repository
6m 24s
* Creating the Controller
6m 14s
* Demo: Creating the Controller
3m 10s
* Demo: Creating the Controller
4m 19s
* Adding the View
7m 26s
* Demo: Creating the View and the ViewModel
8m 26s
* Adding Different View Files
2m 15s
* Demo: Adding a Layout, ViewImports and ViewStart
4m 17s
* Styling the View
1m 51s
* Demo: Styling the View
4m 43s
* Summary
0m 46s

# 5. Working with Real Data Using Entity Framework Core
`Module length:31m 58s`
* Module Introduction
1m 35s
* Hello EF Core
3m 48s
* Adding EF Core to the Application
3m 18s
* Demo: Adding the Packages and Creating the Context
6m 39s
* Querying and Modifying Data
1m 47s
* Demo: Creating the Real Repository
4m 58s
* Creating and Initializing the Database
1m 55s
* Demo: Creating and Initializing the Database
4m 53s
* Modifying the Model
0m 46s
* Demo: Updating the Database
1m 27s
* Summary
0m 47s

# 6. Adding Navigation to the Site
`Module length:25m 36s`
* Module Introduction
1m 0s
* Understanding Routing in ASP.NET Core MVC
5m 39s
* Configuring the Routing System
4m 23s
* Navigation with Tag Helpers
5m 13s
* Demo: Adding Navigation
8m 41s
* Summary
0m 36s

# 7. Improving the Views in the Application
`Module length:48m 54s`
* Module Introduction
1m 14s
* Using Partial Views
2m 46s
* Demo: Working with Partial Views
2m 56s
* Demo: Creating the Home Page
4m 36s
* Creating the Shopping Cart
2m 12s
* Demo: Creating the Shopping Cart
14m 43s
* Adding View Components
4m 27s
* Demo: Adding View Components
7m 34s
* Creating a Custom Tag Helper
2m 28s
* Demo: Creating the Email Tag Helper
4m 42s
* Summary
1m 11s

# 8. Creating an Order Form
`Module length:30m 14s`
* Module Introduction
1m 13s
* Using Tag Helpers to Create the Form
3m 25s
* Demo: Creating an Order Form
8m 7s
* Understanding Model Binding
3m 30s
* Demo: Using Model Binding
4m 31s
* Adding Validation
5m 39s
* Demo: Adding Validation to the Form
3m 9s
* Summary
0m 38s

# 9. Adding Login Capabilities to the Site
`Module length:23m 26s`
* Module Introduction
1m 1s
* Exploring ASP.NET Core Identity
3m 45s
* Demo: Preparing the Site for ASP.NET Core Identity
3m 25s
* Adding Authentication
5m 7s
* Demo: Adding Login and Registration Functionality
6m 6s
* Enabling Authorization
1m 52s
* Demo: Authorizing Users to Place an Order
1m 24s
* Summary and Course Closing
0m 43s


# Course Materials

---
# READING
- .[Microsoft eShopOnWeb ASP.NET Core Reference Application](https://github.com/DebasisPaul/eShopOnWeb)
- [ASP.NET Core Developer Roadmap](https://github.com/DebasisPaul/AspNetCore-Developer-Roadmap)
- [Training Tutorial](https://github.com/DebasisPaul/training-tutorials/blob/master/content/asp.net/getting-started/README.md)
- [Web Camp Training Kit](https://github.com/DebasisPaul/WebCampTrainingKit)
- [Practical ASP NET Core](https://github.com/DebasisPaul/practical-aspnetcore)
- [ASP Net Core Concepts Workshop](https://github.com/DebasisPaul/aspnetcore-concepts-workshop)
- [DotNet Tutorial](https://dotnettutorials.net/lesson/introduction-to-asp-net-core/)
- [Tutorials Teacher](https://www.tutorialsteacher.com/core/dependency-injection-in-aspnet-core)
- [W3School](https://www.w3schools.com/asp/default.asp)
- [ASP.NET Core MVC Tutorial for Beginners](https://www.pragimtech.com/courses/asp-net-core-mvc-tutorial-for-beginners/)
- [TutorialPoint](https://www.tutorialspoint.com/asp.net_core/index.htm)
- [guru99](https://www.guru99.com/asp-net-tutorial.html)
- [TekTutorialsHub](https://www.tektutorialshub.com/asp-net-core-tutorial/)
- [Learn ASP.NET Core: Beginner to Advanced Course](https://www.dotnettricks.com/paths/become-asp-net-core-developer)
- [LinkedInLearning](https://www.linkedin.com/learning/)

# Books
- ASP.NET Core in 24 Hours, Sams Teach Yourself
