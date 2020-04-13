# C# Self-learn 13th April 2020

## Preface
This project was created so that I could learn and understand C# using Visual Studio Code (VSC) on my own. I Googled on C# basics for VSC and found this [website](https://docs.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code). So I just followed that small tutorial but I am still confused as to what and how C# is written. 

## Objectives
- [x] learn how to setup the environment
- [ ] learn the syntax
- [ ] create a simple webpage (since I studied full-stack dev)

### 13 April Notes :
What I have learned and understood so far was how to create the environment. 

Pre-requisites for setting up: 
- Installed [VSC](https://code.visualstudio.com/)
- Installed [.NET SDK](https://dotnet.microsoft.com/download)
- Insalled [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) on Visual Studio Code (VSC)

To setup the environment:
1. Open and create a new folder in VSC. 

    The usual way I do is through CMD terminal (not Powershell). But you can just open up VSC, create new project then create new folder.

    If you want to try using my way: 
    - Press "Windows key" + "r"
    - Press "Ctrl" + "Shift" + "Enter" (to enable Admin)
    - Allow admin control
    - key in "mkdir _name-of-project_" into the terminal and press "Enter" (creates _name-of-project_ folder)
    - key in "cd _name-of-project_" and press "Enter" (makes you enter the _name-of-project_ folder)
    - Key in "code ." and press "Enter" (take note of the dot)

2. Create the C# environment.

    Open up the terminal in VSC (look for the Terminal tab at the top of the screen) and enter the following:
    ```
    dotnet new console
    ```

    This would build up a simple boiler plate code for you. It has the "Hello World" demo written inside. 

3. Resolve build assets.

    Key in the following into the terminal: 
    ```
    dotnet restore
    ```

    For my case, I realised that it had automatically run it for me when I ran the previous ```dotnet new console``` command.

4. Try running the pre-built code.

    Key in the following into the terminal:
    ```
    dotnet run
    ```

    If all goes well, your terminal will show "Hello World."


