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
       2. You can comment muktile lines by using in start line "/* " then the last line you want to comment use "*/"
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
            /* var a = "Ahmad"; 
           console.writeLine(a);
           */
        }
   }
  }
```



### Data Types:
1. String
 
    * In this section we learn one of data types **string**, and how to declare it.

```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            string myName = "Ahmad"; 
            console.writeLine(a);
          
        }
   }
  }
```


2. int
    * In this section we learn one of data types **int**, and how to declare it.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            string myName = "Ahmad";
            var myName2 = "Ahmad";
            console.writeLine(myName + "" + myName2);
          
        }
   }
  }
```

3. Double
   * In this section we learn one of data types **Double**, and how to declare it.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            double firstDouble = 4.8;
            var secondDouble = 4.9;
            console.writeLine(a);
          
        }
   }
  }
```

4. Boolean.
   * In this section we learn one of data types **Double**, and how to declare it.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            double firstDouble = 4.8;
            var secondDouble = 4.9;
            console.writeLine(a);
          
        }
   }
  }
```
5. Constatn in c#
     * In this section we learn one of data types **constant**, and how to declare it.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
            const int constantInt = 13;
            console.writeLine(constantInt);
          
        }
   }
  }
```

### Conditions
* You can use these conditions to perform different actions for different decisions.

![image](https://github.com/Ahmadam37/cSharpLanguage/assets/51037193/d9bcf43f-bfb6-4091-b655-0457c2e518ef)


1. if condition:
    * Here we will use **if** condition, and we will know how to work and how to declare it.
        * In this program the **if** condition will check the value of "age" and if the value greater than 18 the program will print "adult".
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
           int age = 13;
           if(age >= 18 ){
               console.writeLine(adult);
             }
        }
   }
  }
```

2. if with else condition
   * Here we will learn how to use **if** with **else** and how to declare it.
       * In this program the **if** condition will check the value of "age" and if the value greater than 18 the program will print "adult" else will print not adult.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
           int age = 13;
           if(age >= 18 ){
               console.writeLine("adult");
             }else{
               console.writeLine("not adult");
             }
        }teenager
   }
  }
```

3. else if condition
   * Here we will learn how to use **if** with **else** and how to declare it.
       * In this program the **if** condition will check the value of "age" and if the value greater than 19 the program will print "adult" else if the age grater than or equal 13 and age lessthan or equal 19 will print teneeger else will print young.
```c#
  using System;

  namespace Project
  {
   class Programm
   {
        static void Main(string[] args)
        {
           int age = 13;
           if(age > 19 ){
               console.writeLine("adult");
             }else if (age >= 13 && age <= 19){
               console.writeLine("teenager");
             }else{
              console.writeLine("young");
             }
        }
   }
  }
```
