# GitHub Copilot in Visual Studio Code

GitHub CoPilot is an AI Pair Programmer, from GitHub products.  supports the developers to convert the comments or the context into code Snippets. GitHub Copilot can be managed through personal accounts with GitHub Copilot for Individuals or through organization accounts with GitHub Copilot for Business.

## Prerequisites
 
- To use GitHub Copilot you must have an active GitHub Copilot subscription
- Latest VsCode IDE must be installed on a developer's machine or GitHub CodeSpaces must be enabled

## Installing the CoPilot Extension

- From the Visual Studio Code Marketplace, search for GitHub CoPilot Extension and click on install.
- 
  ![image](https://github.com/user-attachments/assets/34c4528b-796b-4118-a524-07ede6497e53)



- After Installing the Extension, sign in with your GitHub Account for activating CoPilot

  ![image](https://github.com/user-attachments/assets/110794a4-fae8-4356-91df-2e780ae0d263)

  ![image](https://github.com/user-attachments/assets/ba5337ab-77f1-41dc-90d5-7e2779509953)

- Sign in with your GitHub account which has been allocated with a CoPilot License

  ![image](https://github.com/user-attachments/assets/676691a8-7b52-42ca-b27f-06759d49d1af)


- Once Signed in, check if Copilot is activated

  ![image](https://github.com/user-attachments/assets/a41b16f7-bb15-4c27-8d39-1e39ce5b136f)


## Working with Copilot

### Using Comments 

### Example-1
- Create a script to start express server 
- Create a new Javascript file and add a comment to create and start the express server

  ![image](https://user-images.githubusercontent.com/67369513/220262763-42ab36fc-877a-48da-916b-24b42dd485ee.png)

- Press Ctrl + Enter to see all the CoPilot Suggestions. Choose the best solution 

  ![image](https://user-images.githubusercontent.com/67369513/220276559-35f96b38-d8c3-4159-b50d-597e9082515c.png)

  ![image](https://user-images.githubusercontent.com/67369513/220276809-688b9cb6-e598-408c-aa5a-c13c8b17eb65.png)

- Test if express server can be initiated

  ![image](https://user-images.githubusercontent.com/67369513/220277431-d4ccf690-ac3c-47b8-9648-ebc826dee923.png)

  ![image](https://user-images.githubusercontent.com/67369513/220264050-59ecfa2b-2c30-46ee-92f3-302e360defc5.png)


### Example-2:
1. Create a new file **githubrepos.js**

2. Add a brief comment 
   ```
   //Desciption: This script will use github api to get the repository size from all repositories in a github organization. 
   ```

    ![image](https://user-images.githubusercontent.com/67369513/220420397-fbf161be-4ffc-472a-b522-23a47addbe51.png)

3. CoPilot will give suggestions on the libraries to use for running your script. Choose an appropriate inline suggestion or add your own inputs

    ![image](https://user-images.githubusercontent.com/67369513/220421202-2f631ae8-7a6a-425b-9422-722ac04f8238.png)

4. Add variables to accept github organization name and github token as inputs to authenticate with the GitHub API

   ![image](https://user-images.githubusercontent.com/67369513/220564471-6ff82f15-2afb-415f-9232-f091bd300c18.png)

5. Add a comment to get the repository size. Add a function name, copilot will give suggestions on the required code to get the repository size information. Choose the appropriate inline suggestion

    ![image](https://user-images.githubusercontent.com/67369513/220424608-09072c53-10c5-45fd-9d08-c4ab9713b10d.png)

6. Add a new comment to create the csv file, copilot will populate a suggestion. Choose the required one and make changes if necessary

    ![image](https://user-images.githubusercontent.com/67369513/220425309-ee284d39-69fe-4fd7-84be-525bbfa563fb.png)

7. Copilot will automatically suggest to add lines for writing the repository data to csv file. 

    ![image](https://user-images.githubusercontent.com/67369513/220426043-c4c41371-e403-438a-bd42-64758412593c.png)

    ![image](https://user-images.githubusercontent.com/67369513/220426227-a562fee7-2ac0-4402-9134-80777b416bf6.png)

    ![image](https://user-images.githubusercontent.com/67369513/220510839-8528bc80-529a-4a4b-8b30-99c90e3a7bf3.png)

8. Add a package.json or run npm init and install the required modules by running npm install

    ![image](https://user-images.githubusercontent.com/67369513/220511267-e2a4c262-3a54-4250-ad2f-dc46d36cce27.png)

9. Run the script by running command node githubrepos.js. Check the generated csv file
    
    ![image](https://user-images.githubusercontent.com/67369513/220512804-7a4d7812-c546-4d83-8840-3f174c214640.png)


## Keyboard shortcuts for GitHub Copilot
### Keyboard shortcuts for macOS

Action | Shortcut | Command name
--- | --- | ---
Accept an inline suggestion |	Tab |	editor.action.inlineSuggest.commit
Dismiss an inline suggestion |	Esc	| editor.action.inlineSuggest.hide
Show next inline suggestion	 | Option (⌥)+]| editor.action.inlineSuggest.showNext
Show previous inline suggestion	| Option (⌥)+[|editor.action.inlineSuggest.showPrevious
Trigger inline suggestion |	Option (⌥)+\ |editor.action.inlineSuggest.trigger
Open GitHub Copilot (additional suggestions in separate pane)	|Ctrl+Return	|github.copilot.generate
Toggle GitHub Copilot on/off	|No default shortcut|github.copilot.toggleCopilot

### Keyboard shortcuts for Windows

Action	|Shortcut	|Command name
--- | --- | --- 
Accept an inline suggestion	|Tab	|editor.action.inlineSuggest.commit
Dismiss an inline suggestion	|Esc	|editor.action.inlineSuggest.hide
Show next inline suggestion	|Alt+]	|editor.action.inlineSuggest.showNext
Show previous inline suggestion |	Alt+[	|editor.action.inlineSuggest.showPrevious
Trigger inline suggestion	|Alt+\	|editor.action.inlineSuggest.trigger
Open GitHub Copilot (additional suggestions in separate pane)	|Ctrl+Enter	|github.copilot.generate
Toggle GitHub Copilot on/off	|No default shortcut |github.copilot.toggleCopilot

### Keyboard shortcuts for Linux

Action	|Shortcut	|Command name
--- | --- | ---
Accept an inline suggestion	|Tab	|editor.action.inlineSuggest.commit
Dismiss an inline suggestion	|Esc	|editor.action.inlineSuggest.hide
Show next inline suggestion	|Alt+]	|editor.action.inlineSuggest.showNext
Show previous inline suggestion	|Alt+[	|editor.action.inlineSuggest.showPrevious
Trigger inline suggestion	|Alt+\	|editor.action.inlineSuggest.trigger
Open GitHub Copilot (additional suggestions in separate pane)	|Ctrl+Enter	|github.copilot.generate
Toggle GitHub Copilot on/off	|No default shortcut |github.copilot.toggleCopilot

## Slash commands

`/tests`: Generate unit tests for the selected code
`/fix`: Propose a fix for problems in the selected code  
`/explain`: Explain the selected code  
`/clear`: Start a new chat
`@workspace`: Has context about the code in your workspace. Use `@workspace` when you want Copilot to consider the structure of your project, how different parts of your code interact, or design patterns in your project.
`@vscode`: Has context about Visual Studio Code commands and features. Use `@vscode` when you want help with Visual Studio Code.
`@terminal`: Has context about the Visual Studio Code terminal shell and its contents. Use `@terminal` when you want help creating or debugging terminal commands.
`@azure`: Has context about Azure services and how to use, deploy and manage them. Use `@azure` when you want help with Azure. The @azure chat participant is currently in public preview and is subject to change.

## Chat variables

Use chat variables to include specific context in your prompt. To use a chat variable, type `# ` in the chat prompt box, followed by a chat variable. Chat variables include:
`#file`: Include a specific file as context in the chat.
`#git`: Include information about the current Git repository.
`#terminalLastCommand`: Include the last run command in the active Visual Studio Code terminal.
