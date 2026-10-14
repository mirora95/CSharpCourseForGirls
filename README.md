# C# Programming Course (Girls Edition)
C# lessons and practice projects for girls learning programming. The lesson notes are written in Russian.

## Course Overview
Start with the introduction, then follow the available lessons in order:

1. [Introduction and development environment](lessons/lesson1.md)
2. [Variables, types, operators, and expressions](lessons/lesson2.1.md)
3. [Conditions and switch expressions](lessons/lesson2.2.md)
4. [Git and GitHub](lessons/lesson3.md)
5. [Loops](lessons/lesson4.1-Loops.md)
6. [Arrays](lessons/lesson4.2-Arrays.md)
7. [Methods and scope](lessons/lesson5.md)
8. [Exception handling](lessons/lesson6.md)
9. [Classes and objects](lessons/lesson7-Class.md)
10. [Windows Forms](lessons/lesson8-WF.md)
  
## Getting Started
You need Git and the .NET SDK to run the console examples. The checked-in projects target `net7.0`, so running them normally also requires the .NET 7 runtime. .NET 7 is [out of support](https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core); these are legacy learning examples, and new projects should use a supported .NET release.

Clone the repository and enter its directory:

```sh
git clone https://github.com/mirora95/CSharpCourseForGirls.git
cd CSharpCourseForGirls
```

Run the first console example from the repository root:

```sh
dotnet run --project projects/lesson1/lesson1/lesson1.csproj
```

It asks `Hello, Where are you from?` and echoes the text you enter.

Run the second example:

```sh
dotnet run --project projects/lesson1/lesson2/lesson2.csproj
```

It prints `Hello, World!` followed by `Clone from GitHub`.

For Visual Studio, open [projects/lesson1/lesson1.sln](projects/lesson1/lesson1.sln), which contains both console projects. The Windows Forms lesson requires Windows and Visual Studio with the .NET desktop development workload.
   
## Contributions
Contributions to this course are highly appreciated. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request on GitHub.

## License
This course is licensed under the [Mozilla Public License 2.0](LICENSE). 
