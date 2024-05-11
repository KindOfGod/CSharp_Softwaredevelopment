---
html:
  embed_local_images: true
  embed_svg: true
  offline: true
  toc: false

print_background: true
export_on_save:
  html: true
---

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
Programming consists of writing instructions for the program to execute. The `Main` method is the entry point of a C# program. 
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

<details><summary>📌 Tipp</summary>
<pre>
- Try using the `Console.WriteLine()` method at the entry point of your program to display your name.
</pre>
</details>
<br>

[🔍 Solution: Exercise 1](../exercise_solutions/exercise1.html)

## 💡 Variables and Data Types

### Declaring Variables

Variables are used to store data in a program. A declaraton of a variable consists of a data type and a name and optionally an initial value. You can think of a variable as a box that holds a value. A declaration of a variable looks like this:

``` csharp
int age = 25;
```

In this example, we declare a variable named `age` of type `int` (integer) and assign it the value `25`. The `int` data type is used to store whole numbers. We use the `=` operator to assign the right value to the variable on the left side.


Here are some common data types:

``` csharp
int age = 25;
double weight = 70;
char gender = 'M';
string name = "Max Mustermann";
```

- `int`: Used to store whole numbers (e.g., 1, 2, 3).
- `double`: Used to store decimal numbers (e.g., 1.5, 2.75).
- `char`: Used to store single characters (e.g., 'A', 'B', 'C').
- `string`: Used to store text (e.g., "Hello, world!").

You can use `var` to declare a variable without specifying the data type explicitly. The programm will automatically try to determine the data type based on the value you assign to the variable.

``` csharp
var age = 25;
```

### Using Variables

Once you've declared a variable, you can use it in your program. For example like this:

``` csharp
var x = 10;
var y = 20;

var sum = x + y; // sum = 30

var product = x * y; // product = 200

var difference = x - y; // difference = -10

var quotient = y / x; // quotient = 2
```

## ⚡️ Exercise 2
In this exercise, you'll write a simple C# program that calulates the square value of a given number.
The number should be stored in a variable and the square value should be calculated and stored in another variable.
Output the result to the console.

<details><summary>📌 Tipp</summary>
<pre>
- Try calculating the product of your two variables.
- Try using the `Console.WriteLine()` method to output the result.
</pre>
</details>
<br>

[🔍 Solution: Exercise 2](../exercise_solutions/exercise2.html)

## 💡 Console Input

So far, we've only been outputting information to the console. But what if you want to get information from the user? In C#, you can use the `Console.ReadLine()` method to read input from the console. Here's an example:

``` csharp
Console.ReadLine();
```

You can store the input in a variable like this:

``` csharp
var x = Console.ReadLine(); //Note: The return value of `Console.ReadLine()` is a string
```
If you want to convert the input to a different data type, you can use the `Convert` class. 
For example, to convert a string to an integer, you can use the `Convert.ToInt32()` method.
Compare these two examples:

Programm 1:
``` csharp
var x = Console.ReadLine();
Console.WriteLine(x + x);
```
```
Input: 5
Output: 55
```
Programm 2:
``` csharp
var x = Console.ReadLine();
var y = Convert.ToInt32(x)
Console.WriteLine(y + y);
```
```
Input: 5
Output: 10
```

## ⚡️ Exercise 3
In this exercise you'll write a programm, which takes in the user's name and brith year as input and outputs a greeting message with the user's name and age.
Calculate the age of the user based on the current year. Output a greeting message with the user's name and age to the console.

Important: Ask the user for the inputs he should provide.

⭐ Bonus: Try using the `DateTime.Now.Year` property to get the current year.

<details><summary>📌 Tipp</summary>
<pre>
- Try using the `Console.ReadLine()` method to read the user's input.
- Try using the `Convert.ToInt32()` method to convert the age input to an integer.
- You can assign the current year to a variable "manually" or use the `DateTime.Now.Year` property.
- Try calculating the age of the user based on the current year minus the birth year.
- Try using the `Console.WriteLine()` method to output the greeting message.
</pre>
</details>
<br>

[🔍 Solution: Exercise 3](../exercise_solutions/exercise3.html)

----

[↩ Back to Contents](../csharp_beginner_introduction.html)

[👉 Next Chapter: Chapter 2](../chapters/chatper2.html)

[🏠 Back to C# Beginner Course](../../../Introduction.html)