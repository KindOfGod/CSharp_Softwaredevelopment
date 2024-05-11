# 🔍 Solution for Exercise 3

## </> Programm
``` csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        // Ask the user for their name
        Console.WriteLine("Please enter your name:");
        var name = Console.ReadLine();

        // Ask the user for their birth year
        Console.WriteLine("Please enter your birth year:");
        var inputYear = Console.ReadLine();

        // convert the input to an integer
        var birthYear = Convert.ToInt32(inputYear);

        var currentYear = 2024; //Alternative: "var currentYear = DateTime.Now.Year;"

        // Calculate the age of the user
        var age = currentYear - birthYear;

        // Output a greeting message with the user's name and age
        Console.WriteLine($"Hello {name}, you are {age} years old.");
    }
}
```

## 🤖 Input / Output:
```
Output: Please enter your name:
Input: John
```
```
Output: Please enter your birth year:
Input: 1990
```
```
Output: Hello John, you are 34 years old.
```

[↩ Back to Chapter 1](../chapters/chapter1.md)