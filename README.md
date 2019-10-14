# Developing modern web applications with ASP.NET MVC

## Objectives

An introduction to the design of modern web applications.

Upon completion of this training students will be able to:
- Create a high quality code in C#.
- Create unit tests with MS Unit Testing and Moq frameworks.
- Design and create a simple web application using ASP.NET framework.


## Training Requirements

* Strong motivation and desire to learn.
* Basic programming languages skills - ability to read and create a simple algorithm.
* Experience in creating simple C# applications.
* English - A2+.


## How to work with tasks?

1. Create a new private repository - [help](https://help.github.com/en/articles/create-a-repo).
2. Add "anzhelikakravchuk" to your repository as collaborator - [help](https://help.github.com/en/articles/inviting-collaborators-to-a-personal-repository). 
3. Complete a task.
4. Upload a task file to your repository - [help](https://help.github.com/en/articles/editing-files-in-your-repository).


## Tasks

1. Getting the amount of vowels in a string - [task01-vowel-count.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task01-vowel-count.cs).

2. Sorting an array - [task02-sort-array.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task02-sort-array.cs).

3. Filtering values in an array - [task03-filter.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task03-filter.cs).

4. Finding a min and max values in jagged arrays - [task04-find-min-max.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task04-find-min-max.cs).

5. Getting a list of prime numbers in a specified range - [task05-prime-numbers.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task05-prime-numbers.cs).

6. Using class and methods modifiers - [task06-modifiers.cs](https://github.com/epam-dotnet-lab/aspnet-training/blob/master/tasks/task06-modifiers.cs).

### Task Tools

Consider using these tools for completing tasks: [repl.it](https://repl.it/languages/csharp), [.NET Fiddle](https://dotnetfiddle.net/) or [LINQPad](https://www.linqpad.net/).

Fiddles for tasks:

* [Task 1](https://dotnetfiddle.net/KkR2Hi)
* [Task 2](https://dotnetfiddle.net/w6sh6N)
* [Task 3](https://dotnetfiddle.net/7LrOey)
* [Task 4](https://dotnetfiddle.net/pqMkM3)
* [Task 5](https://dotnetfiddle.net/2TKkqQ)
* [Task 6](https://dotnetfiddle.net/xSk1L3)


 ### Content 
   - Creating types in C# 
      - Value and Reference Types.
      - Classes vs Struct. 
      - Boxing and Unboxing. 
      - Naming conventions.
      - Static and instance class.
      - Type members - Fields, Constructors, Methods (Property, Indexers, Operators , Event - preview), Nested types. Enum. 
   - Encapsulation. Inheritance. Polymorphism  
      - Encapsulation. Access modifiers. Properties. Automatic properties. Indexers.
      - Inheritance.
      - Sealed Methods and Classes.
      - Special Base Types - System.ValueType, System.Enum. Virtual methods.
      - System. Object (Equals, GetHashCode, ToString and etc). Abstract methods.
      - Abstruct classes.
      - Interface Inheritance.
      - Dynamic.
      - Single dispatch and multiple dispatch.  
   - Framework Fundamentals 
      - String and Text Handling (String, StringBuilder).
      - Formatting and Parsing.
      - Dates and Times.
      - Equality Comparison - Standard Equality Protocols. Order Comparison.
      - IComparable versus Equals. 
   - Exception Handling. Logging. NLog 
      - Exception Sources. Exceptions from APIs, your code.
      - Handling exceptions and catch blocks.
      - Nested try blocks.
      - Finally blocks.
      - Throwing exceptions, rethrowing exceptions.
      - Exception types, custom exceptions and unhandled exceptions.
      - Logging and NLog .Net Framework.
      - Configuration (multiple targets, logger-specific routing). 
   - Generics and Collections
      - Generic types.
      - Type constraints: reference type, value type, new(), type inference and etc.
      - Enumeration: IEnumerable, IEnumerator, IEnumerable<T> and IEnumerator<T>.
      - IEqualityComparer and EqualityComparer.
      - IStructuralEquatable and IStructuralComparable .
      - ICollection, IList and IDictionary<TKey,TValue> Interfaces.
      - Lists, Queues, Stacks, Sets and Dictionaries.
      - Customizable Collections and Proxies. 
   - Delegates. Lambdas and Events
      - Delegate types.
      - Creating a delegate.
      - Multicast delegates.
      - Invoking a delegate.
      - Common delegate types.
      - Inline methods (anonymous function and lambda expression).
      - Delegates versus interfaces.
      - Captured variables.
      - Lambdas and expression trees.
      - Events. Standard event delegate pattern. Custom add and remove methods.
      - Events versus delegates. 
   - Introduction to Language Integrated Query (LINQ) 
      - LINQ-to-objects queries: Fluent Syntax and Query Operators.
      - Lambda expressions and Func signatures. Query Expressions. 
      - Supporting Query Expressions. Deferred Evaluation. LINQ, Generics, and IQueryable<T>.
      - Standard LINQ Operators: Filtering, Select, SelectMany, Ordering, Specific Items and Subranges. Set Operations. Joins.
      - Local Queries. 
      - Interpreted Queries (IQueryable preview). Combining Interpreted and Local Queries. 
   - Internal device types in .NET Framework. Resource management 
      - .NET Framework Internals. WinDbg tool.
      - Garbage Collection. Optimization techniques.
      - Events and the Garbage Collector.
      - Weak References and Events.
      - Garbage Collection and Memory Consumption.
      - Finalizers.
      - IDisposable, Dispose, and Close. Рattern Dispose.
   - Streams and I/O
      - Stream Architecture.
      - Using Streams.
      - Stream Adapters, Stream Decorators.
      - File and Directory Operations. 
   - XML Technologies 
      - XML intro.
      - Architectural Overview. 
      - X-DOM Overview.
      - The LINQ to XML DOM. Instantiating an X-DOM. 
      - Navigating and Querying. Updating an X-DOM. 
      - Documents and Declarations.
      - Projecting into an X-DOM. 
      - XmlReader. XmlWriter. 
      - Patterns for Using XmlReader/XmlWriter.
      - XSD and Schema Validation. XSLTXSD, XSLT, XPath. 
   - Serialization
      - Serialization Concepts.
      - Serialization mechanisms in the .NET Framework. Formatters.
      - The Data Contract Serializer.
      - The Binary Serializer.
      - XML Serialization. 
    - Object Oriented Design Principles
      - Principles of software development.
      - SOLID principles.
   - Attributes
      - Applying Attributes.
      - Defining and Consuming Custom Attributes. 
   - ADO.NET intro
      - ADO.NET infrastructure.
      - The Data Provider Model.
      - Connected approach.
      - The SqlConnection Object.
      - The SqlCommand Object.
      - Reading Data with the SqlDataReader.
      - Disconnected approach – The DataSet and SqlDataAdapter.
      - Using Stored Procedures.
   - ADO.NET EF 
      - Entity Framework Basics.
      - Entity Framework Architecture.
      - Entity Framework development approaches Code First. Model First.
      - Database First.
   - The ASP.NET Platform Foundation 
      - The ASP.NET Life Cycles.
      - Modules.
      - Handlers.
      - Disrupting the Request Life Cycle. 
   - Overview of MVC Projects
      - Creating a New ASP.NET MVC Project.
      - The MVC Pattern.
      - Working with Visual Studio MVC Projects. 
   - Controllers and Actions
      - Simulating the ASP.NET MVC runtime.
      - The URL routing HTTP module.
      - Application routes.
      - Aspects of a controller.
      - Writing controller classes.
      - Processing input data.
      - Producing action results.
      - Creating the first application.
   - Views
      - The mechanics of a view engine.
      - Definition of the view template.
      - Basic helpers.
      - Templated helpers.
      - Custom helpers, HTML helper and Ajax helper.
      - Inside the Razor view engine.
      - Modeling the view.
      - Advanced features. 
   - The model-binding architecture 
      - The input model.
      - Model binding.
      - Advanced model binding.
      - Model validation. 
   - Ajax 
      - View on AJAX.
      - Getting to know JavaScript libraries.
      - Performing simple HTML replacement.
      - Using JSON and XML responses. 
   - The ASP.NET Platform Services
      - Configuration.
      - State Data.
      - Caching Data.
      - Caching Content.
      - Security in ASP.NET MVC.
