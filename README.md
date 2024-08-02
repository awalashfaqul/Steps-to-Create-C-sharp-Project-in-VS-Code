# Setting Up a C# Project in Visual Studio Code

Welcome to the world of C# programming! If you're new to C#, this guide will help you set up your first project in Visual Studio Code (VS Code). I'll walk us through installing the necessary tools, setting up our project, and starting our coding journey.

## Prerequisites

Before we get started, we need to install a few tools: .NET SDK, VS Code and C# extentions. Let's get those:

1. **Install .NET SDK**
   - You can visit, download and install the .NET SDK from the [official .NET website](https://dotnet.microsoft.com/download).

2. **Install Visual Studio Code**
   - You can also visit, download and install VS Code from the [official VS Code website](https://code.visualstudio.com/).

3. **Install C# Extension for VS Code**
   To do this step, I will suggest you to - 
   - Open VS Code.
   - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
   - Search for "C#" and install the official C# extension by Microsoft.

## Steps to Create a C# Project in VS Code

### 1. Open a New Terminal in VS Code

We can open a new terminal by going to `View` > `Terminal` or pressing `` Ctrl+` ``.

### 2. Create a New Directory for Our Project

In the terminal, navigate to the directory where we want to create our project. Create a new directory and navigate into it:

```sh
mkdir MyCSharpProject
cd MyCSharpProject
```

### 3. Create a New C# Project

Run the following command to create a new console application:

```sh
dotnet new console
```

This command generates the necessary files for a simple C# console application.

### 4. Open the Project in VS Code

Open the project in VS Code by running:

```sh
code .
```

This command opens the current directory in VS Code.

### 5. Restore Dependencies

In the terminal, run:

```sh
dotnet restore
```

This command restores the dependencies and tools required for the project.

## Exploring the Project Structure

- **Program.cs**: This file contains the main entry point of our application.
- **MyCSharpProject.csproj**: This is the project file where project configurations and dependencies are defined.

## Running Our C# Application

### 1. Open the `Program.cs` File

We should see a basic "Hello World" program in `Program.cs`.

### 2. Run the Application

In the terminal, run:

```sh
dotnet run
```

We should see the output "Hello World!" in the terminal.

## Debugging Our C# Application

### 1. Create a `launch.json` File

To debug our application, we need to create a `launch.json` file:

- Go to the Run and Debug view by clicking the Run icon in the Activity Bar or pressing `Ctrl+Shift+D`.
- Click on "create a launch.json file" and select `.NET Core`.

### 2. Start Debugging

Set breakpoints in our code by clicking in the gutter next to the line numbers. Press `F5` to start debugging. The application will run and stop at our breakpoints.

## Adding Additional Packages

### 1. Install Packages

We can add additional packages using the `dotnet add package` command. For example, to add the Newtonsoft.Json package, run:

```sh
dotnet add package Newtonsoft.Json
```

### 2. Restore Packages

Run `dotnet restore` if necessary to restore the newly added packages.

## Building Our Application

### 1. Build the Project

To build our project, run:

```sh
dotnet build
```

## Summary

By following these steps, we can set up and run a C# project in Visual Studio Code. This setup allows us to take full advantage of the .NET SDK and the powerful features provided by VS Code, such as IntelliSense, debugging, and extensions.

## Contact

Happy coding! If you run into any issues or have questions, feel free to reach out for help. For any questions or feedback, please contact:

- **Name**: [Ashfaqul Awal]
- **Email**: [ashfaq.awal@gmail.com]

---

