# Hello World
---
This readme will let you know how to create a simple Hello World program using C#. To get started you'll need to make sure that you have the following:

1. Visual Studio 2022
1. Git Version Control
1. Windows

With all those installed go ahead and open up Visual Studio 2022, create a new project and choose the Console App option from the choices listed.

![Console App](https://i.gyazo.com/b4137beb94410b2f6911e137b2d6eed8.png)
You'll be presented with a template already which you can either overwrite or add to by entering in the following code:

```csharp
using System;

namespace MyHelloWorldApp
{
    class Program
    {
       static void Main(string[] args)
        {
            Console.WriteLine("Hello World");
        }
    }
}
```
I recommend typing out your code manually whenever possible as you'll have access to the handy tooltips which will create a drop down after writing out some class names that will include all the methods related with the class. As an example when you type out the Console class you'll be presented with a list of methods contained within Console which includes the WriteLine method which is what we used to display our Hello World message in the console when we run our program.

![Gif Test](https://i.gyazo.com/1b493bbe211d43c91dc9803f50cdefa9.gif)

Here's a checklist
