MVCDEMO
=======

ASP.NET MVC Application Using Entity Framework Code First

livedemo(mvcdemo-4.apphb.com)

A Visual Studio project which shows how to use the Entity Framework in an ASP.NET MVC web application project, using the Code First development approach. The code illustrates the following topics:

Creating a data model using data annotations attributes, and fluent API for database mapping.
Performing basic CRUD operations.
Filtering, ordering, and grouping data.
Working with related data.
Handling concurrency.
Implementing table-per-hierarchy inheritance.
Implementing the repository and unit of work patterns.
Performing raw SQL queries.
Performing no-tracking queries.
Working with proxy classes.
Disabling automatic detection of changes.
Disabling validation when saving changes.
A tutorial series(http://www.asp.net/mvc/tutorials/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application) describes how to build the sample application from scratch.






Contoso 大学 - 使用 EF Code First 创建 MVC 应用

Contoso 大学 Web 示例应用演示了如何使用 EF 技术创建 ASP.NET MVC 应用。示例中的 Contoso 大学是虚构的。应用包括了类似学生注册、课程创建以及教师分配等功能。

这个系列教程展示了创建 Contoso 大学应用的步骤。你可以 下载完整 的程序，或者按照教程一步一步创建它，这个教程中使用 C# 进行演示，下载的代码中同时包含 C# 和 VB 实现。如果你有与这个教程没有直接相关的问题，可以张贴到 ASP.NET Entity Framework forum  或者 Entity Framework and LINQ to Entities forum.

这个教程假设你知道如何使用 Visual Studio 来开发 ASP.NET MVC 程序，如果不是这样，basic ASP.NET MVC Tutorial 是不错的起点。如果你以前使用 Web Form 开发，可以先看看 Getting Started with the Entity Framework 和 Continuing with the Entity Framework  教程。

在开始之前，确信下列软件已经安装在你的计算机上：

Visual Studio 2010 SP1 或者 Visual Web Developer Express 2010 SP1 ( 如果你使用这两个链接，下面的项目将会被自动安装 )
ASP.NET MVC 3 Tools Update
Microsoft SQL Server Compact 4.0
Microsoft Visual Studio 2010 SP1 Tools for SQL Server Compact 4.0
这个系列分为 10 个部分：

1 - 为 ASP.NET MVC 应用程序创建 EF 数据模型

2 - 使用 EF 在 MVC 中实现基本的增、删、改、查功能

3 - 排序、过滤与分页

4 - 创建更加复杂的数据模型

5 - 读取关联的数据

6 - 更新关联的数据

7 - 处理并发

8 - 实现继承

9 - 实现仓储和操作单元模式

10 - 高级 EF 应用场景