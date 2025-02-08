# Welcome to Your C# Development Environment

This repository is pre-configured for C# development using Visual Studio Code with the **C# Dev Kit** extension. If you're new to programming or just starting out with C#, this guide will help you set up your environment so you can focus on learning and coding right away.

---

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started in VS Code](#getting-started-in-vs-code)
- [Microsoft Account & License Activation](#microsoft-account--license-activation)
- [Exploring & Running the Sample Project](#exploring--running-the-sample-project)
- [Creating a New .NET Console Application](#creating-a-new-net-console-application)
- [Additional Resources](#additional-resources)
- [Troubleshooting](#troubleshooting)
- [Conclusion](#conclusion)

---

## Prerequisites

Before you begin, ensure you have:

- **Visual Studio Code** installed on your machine.
- A **stable internet connection**.
- A **Microsoft account** (required to activate the C# Dev Kit individual license).  
  *If you don’t have one, create one [here](https://account.microsoft.com/account).*

---

## Getting Started in VS Code

1. **Open the Repository:**
   - Clone or download this repository to your local machine.
   - Open the repository folder in Visual Studio Code.

2. **C# Dev Kit Extension:**
   - The repository is set up to work with the **C# Dev Kit** extension.
   - Once you open the repo, the C# Dev Kit extension will prompt you to install the .NET SDK if it isn’t already installed.
   - Follow the on-screen instructions to complete the SDK installation.

---

## Microsoft Account & License Activation

To access all the features of the C# Dev Kit, you need to activate your individual license:

1. **Sign In:**
   - When prompted by the C# Dev Kit extension, sign in using your Microsoft account.
   
2. **Activate the License:**
   - After signing in, follow any additional prompts to activate your individual license.
   - This activation is necessary to unlock the full capabilities of the C# Dev Kit.

---

## Exploring & Running the Sample Project

This repository includes a basic C# project to help you get started.

1. **Review the Code:**
   - Open the `Program.cs` file in the project folder to see the "Hello, World!" sample code.
   
2. **Modify the Code:**
   - Feel free to experiment by editing `Program.cs`. Change the greeting message or add your own code.

3. **Run the Application:**
   - Open the integrated terminal in VS Code by selecting **Terminal > New Terminal** or using the shortcut:
     - **Windows/Linux:** `Ctrl + \``
     - **macOS:** `` Cmd + ` ``
   - Ensure you are in the repository folder and execute the following command:
     ```bash
     dotnet run
     ```
   - You should see the output from your application (for example, a "Hello, World!" message).

---

## Creating a New .NET Console Application

If you want to start a new project from scratch, follow these steps to create and run a new .NET Console Application:

1. **Create a New Console App:**
   - In the integrated terminal, run:
     ```bash
     dotnet new console -o MyNewApp
     ```
   - This command creates a new directory called `MyNewApp` with a basic "Hello, World!" console application.

2. **Navigate to Your New Project Directory:**
   ```bash
   cd MyNewApp