# C# Programming Language

## Overview
C# (pronounced "C-Sharp") is a modern, object-oriented, and type-safe programming language developed by Microsoft as part of its .NET initiative. It was designed for developing applications on the Microsoft platform, but its usage has expanded to various other domains, such as mobile and game development.

## History
C# was introduced in 2000 by Anders Hejlsberg and Microsoft, initially released as part of the .NET Framework. It has since evolved significantly, with the latest version supporting a wide range of programming paradigms, including functional, imperative, and object-oriented programming.

## Key Features

1. **Object-Oriented**: C# is object-oriented, meaning it supports encapsulation, inheritance, and polymorphism. It provides classes and objects as the building blocks for applications.

2. **Type Safety**: C# is strongly typed, which prevents type errors and helps avoid many common bugs.

3. **Automatic Garbage Collection**: Memory management in C# is handled by the .NET runtime’s garbage collector, which automatically reclaims memory occupied by unused objects.

4. **Rich Library Support**: C# is tightly integrated with the .NET framework, which provides a vast library of built-in functions and utilities for various tasks.

5. **LINQ (Language Integrated Query)**: C# supports querying data in a SQL-like syntax with LINQ, making it easier to work with collections of data.

6. **Asynchronous Programming**: C# supports asynchronous programming patterns using the `async` and `await` keywords, improving the performance of applications by preventing blocking operations.

7. **Cross-Platform Development**: With .NET Core (now known as .NET), C# applications can be built and run on Windows, Linux, and macOS.

## Basic Syntax

### Hello World
```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
