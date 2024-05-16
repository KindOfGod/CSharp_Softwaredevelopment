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

# 📖 Chapter 2
In this section, we will learn about basic conditional statements and loops in C#. We will also learn about arrays and how to use them in C#.

## 💡 If - Statements
The `if` statement is used to execute a block of code only if a specified condition is true. Here's an example:

``` csharp
var condition = true; // Condition can be true or false

if (condition)
{
    // code to be executed if the condition is true
}
```

You can also use an `else` statement to execute a block of code if the condition is false, or an `else if` statement to specify a new condition to test. Here's an example:

``` csharp
var name = "Max"; // Condition can be true or false

if (name == "Thomas")
{
    // code if the condition is true
}
else if (name == "Max")
{
    // code if the condition is true
}
else
{
    // code if both conditions are false
}
```

As you can see in the example above, the `if` statement checks if the `name` variable is equal to "Thomas". If it is, the code block inside the `if` statement is executed. If the condition is false, the `else if` statement checks if the `name` variable is equal to "Max". If it is, the code block inside the `else if` statement is executed. If both conditions are false, the code block inside the `else` statement is executed.

## 💡 Conditions
In C#, you can use various operators to create conditions. Here are some common operators:

- `==` true if the values are equal
- `!=` true if the values are not equal
- `>` true if the left operand is greater than the right operand
- `<` true if the left operand is less than the right operand
- `>=` true if the left operand is greater than or equal to the right operand
- `<=` true if the left operand is less than or equal to the right operand
- `!` true if the operand is false

You can also combine conditions using logical operators:	

- `&&` AND
- `||` OR

Here's an example:

``` csharp
var age = 25;
var isStudent = true;

if (age >= 18 && isStudent)
{
    // code to be executed if the age is greater than or equal to 18 and the person is a student
}
else if (age < 18 && !isStudent)
{
    // code to be executed if the age is less than 18 or the person is not a student
}
else if (age != 18 || !isStudent)
{
    // code to be executed if the age is not equal to 18 or the person is not a student
}
else
{
    // code to be executed if both conditions are false
}
```


## 💡 Switch - Statements

## 💡 Arrays

## 💡 While - Loop

## 💡 For - Loop

----

[↩️ Back to Contents](../csharp_beginner_introduction.html)

[👉 Next Chapter: Chapter 3](../chapters/chapter3.html)

[🏠 Back to C# Beginner Course](../../../Introduction.html)