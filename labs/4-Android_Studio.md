# GitHub Copilot in a JetBrains IDE - Android studio
GitHub CoPilot is an AI Pair Programmer, from GitHub products.  supports the developers to convert the comments or the context into code Snippets. GitHub Copilot can be managed through personal accounts with GitHub Copilot for Individuals or through organization accounts with GitHub Copilot for Business.

## Prerequisites:
 
- To use GitHub Copilot you must have an active GitHub Copilot subscription
   
- To use GitHub Copilot in JetBrains, you must have a compatible JetBrains IDE installed. GitHub Copilot is compatible with the following IDEs.
   
   - IntelliJ IDEA (Ultimate, Community, Educational)
   - Android Studio
   - AppCode
   - CLion
   - Code With Me Guest
   - DataGrip
   - DataSpell
   - GoLand
   - JetBrains Client
   - MPS
   - PhpStorm
   - PyCharm (Professional, Community, Educational)
   - Rider
   - RubyMine
   - WebStorm

### Installing the GitHub Copilot extension in your JetBrains IDE -- Android Studio 

To use GitHub Copilot in a JetBrains IDE -- Android Studio, you must install the GitHub Copilot extension. The following procedure will guide you through installation of the GitHub Copilot plugin in Android Studio.

1. Open the `Android Studio`.

2. In your Android Studio, under the `File` menu, click `Settings`.

3. The new window will pop-up then click `Plugins`/`Marketplace`.

4. In the search bar, search for `Copilot`, then you will find `GitHub Copilot`, click `Install`.
   
   ![image](https://user-images.githubusercontent.com/95218310/220102442-4c4ea1b1-4cdc-42e7-b9de-74bc7f8912a0.png)

5. After GitHub Copilot is installed, click `Restart IDE`.

   ![image](https://user-images.githubusercontent.com/95218310/220103912-4dd2c618-d286-4405-af59-c52307fa92bb.png)

6. After your Android Studio has restarted, click the `Tools` menu. Click `GitHub Copilo`t, then click `Login to GitHub`.
 
   ![image](https://user-images.githubusercontent.com/95218310/220104076-7c4ae4bd-eceb-4d20-8030-8e37dba09bbc.png)

7. In the "Sign in to GitHub" dialog box, to copy the device code and open the device activation window, click `Copy and Open`.

   ![image](https://user-images.githubusercontent.com/95218310/220104241-6a40c27d-e199-4da2-bbbb-bc3a5fd3c36d.png)

8. A device activation window will open in your browser. Paste the device code, then click `Continue`.

  ![image](https://user-images.githubusercontent.com/95218310/220104373-964780da-6d6d-4b48-85ef-5fd09b993e47.png)

9. GitHub will request the necessary permissions for GitHub Copilot. To approve these permissions, click `Authorize GitHub Copilot Plugin`.

   ![image](https://user-images.githubusercontent.com/95218310/220104530-53422cc2-b4b4-45d6-8056-951610f9c852.png)

10. After the permissions have been approved, your Android Studio will show a confirmation. To begin using GitHub Copilot, as below.

    ![image](https://user-images.githubusercontent.com/95218310/220104715-b4b74935-a08c-46ce-bc29-414b585c2972.png)


## Enabling and disabling GitHub Copilot

You can enable or disable GitHub Copilot for all languages, or for individual languages. The GitHub Copilot status icon in the bottom panel of your Android Studio window indicates whether GitHub Copilot is enabled or disabled. When enabled, the icon is highlighted. When disabled, the icon is grayed out.

1. To enable or disable GitHub Copilot, click the status icon in the bottom panel of the Android Studio window.

   ![image](https://user-images.githubusercontent.com/95218310/220105113-c42cfdad-7edf-4bc4-b775-56ecfcdf439b.png)

2. If you are disabling GitHub Copilot, you will be asked whether you want to disable it globally, or for the language of the file you are currently editing.
   
   - To disable suggestions from GitHub Copilot globally, click Disable Completions.
   
   ![image](https://user-images.githubusercontent.com/95218310/220105341-6e49c7fa-47f6-43ad-85fa-160dc07a07a4.png) 
 
   - To disable suggestions from GitHub Copilot for the specified language, click Disable Completions for LANGUAGE.
   
   ![image](https://user-images.githubusercontent.com/95218310/220105461-a563eb8d-904c-48dc-904f-f959122db914.png)

## Shortcuts on the keyboard for GitHub Copilot

You can use the default keyboard shortcuts for inline suggestions in your Android Studio when using GitHub Copilot. Alternatively, you can rebind the shortcuts to your preferred keyboard shortcuts for each specific command.

Action	| Shortcut
--- | ---
Accept an inline suggestion | Tab
Dismiss an inline suggestion | Esc
Show next inline suggestion | Alt+]
Show previous inline suggestion | Alt+[
Trigger inline suggestion | Alt+\
Open GitHub Copilot (additional suggestions in separate pane | Alt+Enter

## Let’s see an example on your first suggestion

GitHub Copilot provides suggestions for numerous languages and a wide variety of frameworks, but works especially well for `Python`, `JavaScript`, `TypeScript`, `Ruby`, `Go`, `C#` and `C++`. The following samples are in `JavaScript`, but other languages will work similarly.

1. In your Android Studio, lets create a sample test-project and then create a new JavaScript (*.js) file.

2. In the file, type the following function header. GitHub Copilot will automatically suggest an entire function body in grayed text, as shown below. The exact suggestion may vary.

  ```
  function calculateDaysBetweenDates(begin, end) {
  ```

  ![image](https://user-images.githubusercontent.com/95218310/220110520-bf138d99-fbb5-4c98-b33f-9db97b3cde3b.png)

3. For any given input, GitHub Copilot may offer multiple suggestions. You can select which suggestion to use or reject all suggestions.

4. To accept a suggestion, press `Tab`. To reject all suggestions, press `Esc`.

## Making code suggestions from comments:

GitHub Copilot will recommend the appropriate code to carry out your request if you use natural language to express anything you wish to do in a comment.

1. In your Android Studio, create a new yaml (*.yml) file.

2. To prompt GitHub Copilot to suggest an implementation of a function in the yaml file, type the following lines.

   ```
   // workflow to upload an artifact to a release
   ```

3. Open a new tab with multiple additional suggestions, Right click and then click Open `GitHub Copilot`

   ![image](https://user-images.githubusercontent.com/95218310/220111493-e4a85233-594f-4d85-9519-ce3c54ee316d.png)

4. Then the new tab will open, with multiple additional suggestions as shown below.

   ![image](https://user-images.githubusercontent.com/95218310/220111564-b8e7e432-19d3-4567-8790-6ff002a6517a.png)

5. To accept a suggestion, above the suggestion, click `Accept Solution`. To reject all suggestions, close the tab.
