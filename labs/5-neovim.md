# GitHub Copilot in Neovim

GitHub CoPilot is an AI Pair Programmer, from GitHub products. Supports the developers to convert the comments or the context into code Snippets. GitHub Copilot can be managed through personal accounts with GitHub Copilot for Individuals or through organization accounts with GitHub Copilot for Business.

## Prerequisites

1. To use GitHub Copilot you must have an active GitHub Copilot subscription
2. Neovim IDE must be installed on a developer's machine. 
3. To use GitHub Copilot in Neovim you must have Neovim version 0.6 or above and Node.js version 17 or below installed

## Download & install

1. To download and install via MSI, open your favourite web browser and visit the Neovim GitHub [release](https://github.com/neovim/neovim/releases) page.
2. Next, scroll down to the assets section, expand it, and click the nvim-win64.msi link to download the installer.

   ![1](https://user-images.githubusercontent.com/92542803/220366127-d55f8d46-5b14-4d5b-bfae-06be2e232525.png)

3. Once downloaded, double-click on the installer to launch the setup wizard.
4. Now, click Next on the welcome screen to continue.

   ![2](https://user-images.githubusercontent.com/92542803/220366694-c82506cc-ed5c-48aa-9759-bc0a4c459586.png)

5. Click Finish once the installation completes, closing the setup wizard.
   
   ![3](https://user-images.githubusercontent.com/92542803/220367351-cd173a57-4c6f-4767-a64e-745ec07484af.png)

6. Open PowerShell as administrator and run the nvim command below to check the version installed on your computer.

   ![4](https://user-images.githubusercontent.com/92542803/220367977-d4ee6988-8c2d-4787-9039-f7b26acf8707.png)

## Installing the Neovim extension

1. GitHub recommends that you install the GitHub Copilot plugin with Neovim's built-in plugin manager. Alternatively, you can use a plugin manager of your choice to install **github/copilot.vim**.

   - To install GitHub Copilot with Neovim's built-in plugin manager, enter the following command in Git Bash.
   
   ```
   git clone https://github.com/github/copilot.vim.git `
   $HOME/AppData/Local/nvim/pack/github/start/copilot.vim
   ```
   
2. Type **neovim** from your powershell prompt.
   
   ![6](https://user-images.githubusercontent.com/92542803/220370921-6e3360f4-047c-4831-8c47-eac8aee5b038.png)

2. Press **ENTER** or type command to continue.
   
   ![7](https://user-images.githubusercontent.com/92542803/220371100-6e497279-4547-422f-ac90-062d730e6b2b.png)

3. To configure GitHub Copilot, enter the following command.
   
   ```
   :Copilot setup
   ```
   ![5](https://user-images.githubusercontent.com/92542803/220370243-d62d1d7d-a444-4a44-8837-16dbb3beecf0.png)

4. First copy your **one-time code**. Press **ENTER** to open GitHub in your browser.
   
   ![8](https://user-images.githubusercontent.com/92542803/220371556-8c2c2332-2060-419e-a28b-5c9cfb12f4c2.png)
   
   ![9](https://user-images.githubusercontent.com/92542803/220371788-5c64379a-98f4-46c5-82d9-4a8ea5dec7f5.png)

5. Authorize GitHub Copilot Plugin.
   
   ![10](https://user-images.githubusercontent.com/92542803/220372199-6478f300-8dfa-41db-b004-b0a04ac23ce5.png)
   
   ![11](https://user-images.githubusercontent.com/92542803/220372206-bcca396f-7fa1-49a2-b3c8-36fdd14de064.png)
   
   ![12](https://user-images.githubusercontent.com/92542803/220372208-5ac22d6b-4c9a-4520-bf67-69f4d694cc63.png)

6. You should see the **Getting started** message and the help commands.

   ![13](https://user-images.githubusercontent.com/92542803/220372604-948d83c7-0264-4f25-8f23-b948660f1163.png)

