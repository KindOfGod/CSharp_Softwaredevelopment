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

# 🔍 Chapter 2: Solution for Exercise 1

## </> Programm
``` csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        //read a number from the console
        Console.WriteLine("Please enter a number:");
        var input = Console.ReadLine();

        //convert the input to an integer
        var number = Convert.ToInt32(input);

        var isEven = number % 2 == 0;

        //check if the number is even or odd
        if (isEven)  
        {
            Console.WriteLine("The number is even.");
        }
        else
        {
            Console.WriteLine("The number is odd.");
        }
    }
}
```

## 🤖 Output:

##### Case 1:
```
Output: Please enter a number:
Input: 10
```
```
Output: The number is even.
```

##### Case 2:
```
Output: Please enter a number:
Input: 7
```
```
Output: The number is odd.
```

----

[↩️ Back to Chapter 2](../../chapters/chapter2.html)