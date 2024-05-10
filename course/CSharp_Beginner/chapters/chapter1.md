# 📖 Chapter 1

In this section, we'll cover the fundamental building blocks of C# programming, including how to output information to the console, receive input from the user, declare variables, and understand various data types.

## 💡 My First Program

``` csharp
using System;

//This is called a class
class Program
{
    //This is called a "method"
    static void Main(string[] args)
    {
        // You can insert your code here as this is the entry point of your program.
    }
}
```
Programming consists of writing instructions for the computer to execute. The `Main` method is the entry point of a C# program. 
When you run a C# program from the command line, the `Main` method is the first method that gets executed.

For now, you can ignore the `using System;` and `class Program` lines. We'll explain them in more detail later. The important part is the `Main` method, which is where you'll write your code.

## 💡 Comments

Comments are lines of text that are ignored by the computer. They are used to document your code and make it easier to understand. In C#, you can write comments using `//` for single-line comments or `/* */` for multi-line comments. For example:

``` csharp
// This is a single-line comment
```
``` csharp
/* This is a multi-line comment
   that spans multiple lines */
```

## 💡 Console Output

The console is a text-based interface where you can display information to the user. In C#, you can use the `Console.WriteLine()` method to output text to the console. Here's an example:

``` csharp
Console.WriteLine("Hello, world!");
```

## ⚡️ Exercise 1
In this exercise, you'll write a simple C# program that displays your name on the console.

Tipp: Use the `Console.WriteLine()` method to output your name.

<details><summary>📌 Tipp</summary>
<pre>
- Try using the `Console.WriteLine()` method at the entry point of your program to display your name.
</pre>
</details>
<br>

[🔍 Solution: Exercise 1](../exercise_solutions/exercise1.md)