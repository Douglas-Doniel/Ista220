-- Name: Douglas Doniel
-- File: cssbs-hw01-Doniel
-- Date: January 14,2021





1. What is a console app?
A console application is an application that runs in a Command Prompt window instead of providing a graphical user interface (GUI)

2. List two differences between .NET Framework and .NET Core. Note that in this class, we will be
writing C# applications in .NET Framework and ASP.NET applications in NET Core.
You use the .NET Core template for building portable applications that can also run on other operating systems, such as Linux
.NET Core applications do not provide the range of features available to the complete .NET Framework

3. What does Main() (the main method) do in a console application?
The Main method designates the program’s entry point.

4. Describe these three files: TextHello.sln, TextHello.csproj, and AssemblyInfo.cs.
This is the top-level solution file. Each application contains a single solution file. A solution can contain one or more projects, and Visual Studio 2017 creates
the solution file to help organize these projects.

Each project file references one or more files containing the source code and other artifacts for the project, such as graphics images.

AssemblyInfo.cs is a special file that you can use to add attributes to a program, such as the name of the author, the date
the program was written, and so on


5. What is the purpose of a namespace?
Creates a container for items such as classes. Two classes with the same name will not be confused with each other if they live in different namespaces.

6. Describe specifically what using statements do.
using statements enable you to bring a class into scope and omit the class name when accessing static member


7. What is the entry point for a console app? What is the entry point for a UWP app?
Main method is the entry point for a console app. App.xaml is the entry point for UWP app

8. What is an assembly?
An assembly is a file that usually has the .dll file name extension, although strictly speaking, executable
programs with the .exe file name extension are also assemblies

9. How many different versions of the WriteLine() method does the Console class contain?
19 different versions


10. What is the relationship between an assembly and a namespace?
 A single assembly can contain classes defined in many namespaces, and a single namespace can span multiple assemblies
 
11. What is a graphical app?
they enable you to create apps that function on any device on any device that run Windows such as desktop computer tablets and phones

12. What does Build do?
This action compiles the C# code, resulting in a program that you can run

13. (Not in book) What is bytecode? What is Microsoft CIL? Do you think that CIL is bytecode? Why
or why not? Bytecode is a form of instruction set designed for efficient execution by a software interpreter. CIL is bytecode and language of .NET platform
14. What does Debug do?
Detects and removes existing or potential errors


