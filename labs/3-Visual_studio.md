# GitHub Copilot in Visual Studio

GitHub CoPilot is an AI Pair Programmer, from GitHub products.  supports the developers to convert the comments or the context into code Snippets. GitHub Copilot can be managed through personal accounts with GitHub Copilot for Individuals or through organization accounts with GitHub Copilot for Business.

## Prerequisites

- To use GitHub Copilot you must have an active GitHub Copilot subscription

- To use GitHub Copilot in Visual Studio, you must have Visual Studio 2022 17.8 or later of Visual Studio for Windows installed.


## Installing the GitHub Copilot extension in your Visual Studio

To use GitHub Copilot in a Visual Studio, you must install the GitHub Copilot extension. The following procedure will guide you through installation of the GitHub Copilot plugin in Visual Studio.

1.	Open the `Visual Studio 2022 17.8` or latest.

2.	In the Visual Studio toolbar, click `Extensions`, then click `Manage Extensions`.

    ![image](https://user-images.githubusercontent.com/95218310/220261053-0e3204ea-e6a8-4812-a7a8-1d7e50ac936c.png)

3.	In the "Manage Extensions" window, click `Visual Studio Marketplace`, search for the GitHub Copilot extension, then click `Download`.

    ![Picture1](https://user-images.githubusercontent.com/95218310/220261427-42c7e8cf-31c9-4a25-9d83-f7598feaf120.jpg)

4.	Close the "Manage Extensions" window, then exit Visual Studio.

    ![image](https://user-images.githubusercontent.com/95218310/220261478-44adeee2-a160-4ab7-a4df-fbcd5098e3f3.png)

5.	Once the Installation completed relaunch `Visual Studio`.

    ![image](https://user-images.githubusercontent.com/95218310/220261561-8527f29f-4050-4358-aba7-189f35b46a50.png)

6.	Optionally, to check that GitHub Copilot is installed and enabled, go back to `Manage Extensions`, click `Installed` to view your currently installed extensions, then click `GitHub Copilot` to see status information.

    ![image](https://user-images.githubusercontent.com/95218310/220261635-130eaf4c-6b5e-48e9-9bbc-baa63f0274cf.png)

7.	After Successfully installation, Open or create a new project in Visual Studio.

8.	Once open the project, In the "Microsoft Visual Studio" dialog box, to copy your device activation code, click `OK`.

    ![image](https://user-images.githubusercontent.com/95218310/220261729-0f1c6a6a-b0ce-4887-b86f-a022f3f0cbd1.png)

9.	A device activation window will open in your browser. Paste the device code, then click `Continue`.

    ![image](https://user-images.githubusercontent.com/95218310/220261863-d27a5e26-cf2a-4b5d-9e9d-75e3862ed8a0.png)

10.	GitHub will request the necessary permissions for GitHub Copilot. To approve these permissions, click `Authorize GitHub Copilot Plugin`.

    ![image](https://user-images.githubusercontent.com/95218310/220261938-21c9da0f-74bf-4d3e-bcfb-46af419e7eb1.png)

11.	After you approve the permissions, Visual Studio will show a confirmation.

    ![image](https://user-images.githubusercontent.com/95218310/220261995-80cfcc7e-9450-4f5f-9e5d-f237eb5a8f45.png)

  
## Shortcuts on the keyboard for GitHub Copilot

You can use the default keyboard shortcuts in Visual Studio when using GitHub Copilot. Alternatively, you can rebind the shortcuts in the Tools settings for Visual Studio using your preferred keyboard shortcuts for each specific command. You can search for each keyboard shortcut by its command name in the Keyboard Shortcuts editor.

Action | Shortcut | Command name
--- | --- | ---
Show next inline suggestion |	Ctrl+Alt+]	| Tools.Nextsuggestion
Show previous inline suggestion |	Ctrl+Alt+[ | Tools.Previoussuggestion
Trigger inline suggestion	| Ctrl+Alt+\ |	Edit.Copilot.TriggerInlineSuggestion

## Let’s see an example on your first suggestion

GitHub Copilot provides suggestions for numerous languages and a wide variety of frameworks, but works especially well for `Python`, `JavaScript`, `TypeScript`, `Ruby`, `Go`, `C#` and `C++`. The following samples are in `C#`, but other languages will work similarly.

1.	In your `Visual Studio`, lets create a sample-project and then create a new `C#` (*.cs) file.

2.	In the `C#` file, type the following function signature. GitHub Copilot will automatically suggest an entire function body in grayed text, as shown below. The exact suggestion may vary.

    ```
    int CalculateDaysBetweenDates(
    ```

    ![image](https://user-images.githubusercontent.com/95218310/220263065-a9e1537f-ba38-4971-a8f6-8b764852ea99.png)

3.	For any given input, GitHub Copilot may offer multiple suggestions. You can select which suggestion to use or reject all suggestions.

4.	To accept a suggestion, press `Tab`. To reject all suggestions, press `Esc`.

## Making code suggestions from comments

GitHub Copilot will recommend the appropriate code to carry out your request if you use natural language to express anything you wish to do in a comment.

1.	In your Visual Studio, create a new `yaml` (*.yml) file.

2.	To prompt GitHub Copilot to suggest an implementation in the yaml file, type the following lines.

    ```
    // workflow to create a build
    ```

    ![image](https://user-images.githubusercontent.com/95218310/220263256-edac9394-e867-4596-86dc-9b36ae5c2d80.png)

3.	If alternative suggestions are available, you can see these alternatives by pressing `Alt+]` (or `Alt+[`).

4.	To accept a suggestion, press `Tab`. To reject all suggestions, press `Esc`.

## Copilot Chat

1. Navigate to View in your Visual studio and click on GitHub Copilot chat to open chat window.

![image](https://github.com/user-attachments/assets/430abfb8-6fb2-4371-b65a-25ec8a21e09a)

2. Like below the chat will open
![image](https://github.com/user-attachments/assets/43769ea0-d422-45ec-848b-1f3ac718569c)

3. You can start asking code related questions example `write a function to sum all numbers in a list` 
![image](https://github.com/user-attachments/assets/398d69c6-602a-4d3e-a7ac-14a79f953200)

### Slash commands in Copilot chat
Use slash commands to avoid writing complex prompts for common scenarios. To use a slash command, type / in the chat prompt box, followed by a command. Slash commands include:

`/tests`: Generate unit tests for the selected code.  
`/fix`: Propose a fix for problems in the selected code   
`/explain`: Explain the selected code
`/optimize`: Analyze and improve the runtime of the selected code

To see all available slash commands, type / in the chat prompt box. See also Slash commands in the Visual Studio documentation. https://learn.microsoft.com/visualstudio/ide/copilot-chat-context#slash-commands


### References
By default, Copilot Chat will reference the file that you have open or the code that you have selected. You can also use # followed by a file name, file name and line numbers, or solution to reference a specific file, lines, or solution. For example:

Reference a specific file: `Where are the tests in #MyFile.cs?`
Reference multiple files: `How are these files related #MyFile.cs #MyFile2.cs`
Reference specific lines in a file: `Explain this function #MyFile.cs: 66-72?`
Reference the current file: `Is there a delete method in this #solution`

See also Reference in the Visual Studio documentation.

