# c# Language.
This repository contains a guide to learning C#. The guide covers the basics of C#.

### Introduction of C#:

* C# a programming language developed by Microsoft.
* C# startted with name COOL stand for C-like Object Oriented Language.
* Then thay colaborate to be part of .NET framework since 2000.




 **After you install IDE and now we will start to learn the C# language more.**


 ### Let's talk about the code structure, and what we learn from it.

 ```c#
using System;

namespace Project
{
   class Programm
   {
        static void Main(string[] args)
        {
             console.writeLine("Hello World!");
        }
   }
}
```

**Lest take it one by one** 

* The **using System** line means that you are using the System library in your project. Which gives you some useful classes like Console or functions/methods like WriteLine.
* **namespace** in C# are used to organize too many classes so that it can be easy to handle the application.
* **class** is handel all methods for this class.
* **static void Main(string[] args)** in tihs it include **Main** method, it is the start or any application in c#, the **Main** Specifies the action of the class when running
* **console.writeLine("Hello World!");**, this statment will executed by the **Main** method, it will print
> Hello World!


**Now we learn the template structure in C# Language**

* How to Declare a varible in C#?
  ```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
             var a = "Ahmad"; //Here we declare a new varible in c#
             console.writeLine(a);
        }
   }
  }
  ```



* How to get a value from user in c#?

```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
             var a = Console.ReadeLine(); //Here the program will ask the user to insert new value.
             console.writeLine(a);
        }
   }
  }
```


* Comments in c#
   * In this example we can see we have to kind of comments
       1. You can comment one line by using "//" two forward slash.
       2. You can comment muktile lines by using in start line "*/" then the last line you want to comment use "/*"
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            // var a = "Ahmad"; 
            //console.writeLine(a);
            */ var a = "Ahmad"; 
           console.writeLine(a);
           /*
        }
   }
  }
```
