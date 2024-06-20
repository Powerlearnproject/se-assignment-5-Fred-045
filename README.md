[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15300794&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:



 1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.











Steps to Download and Install Visual Studio Code
Download the Installer:


 Here are some of the Prerequisites when installing Visual code 


Operating System: Windows 10 or Windows 11
Disk Space: Approximately more than 5Gb of free space
Internet Connection: To download the installer and any additional extensions or updates

Open your web browser and go to the Visual Studio Code website.
Click on the "Download for Windows" button. This will download the VS Code installer (VSCodeSetup-x64-<version>.exe).
Run the Installer:

Once the download is complete, navigate to your Downloads folder (or the location where you saved the installer).
Double-click the VSCodeSetup-x64-<version>.exe file to run the installer.
Start the Installation:

The Visual Studio Code Setup wizard will open. Click "Next" to proceed.
Accept the License Agreement:

Read through the license agreement, then select "I accept the agreement" and click "Next".
Select Installation Location:

Choose the destination folder where you want to install VS Code. The default location is usually fine. Click "Next" to continue.
Select Start Menu Folder:

Choose the Start Menu folder where you want the Visual Studio Code shortcuts to be created. The default setting is typically fine. Click "Next".
Select Additional Tasks:

You can choose additional tasks such as:
Create a desktop icon.
Add "Open with Code" action to Windows Explorer file context menu.
Add "Open with Code" action to Windows Explorer directory context menu.
Register Code as an editor for supported file types.
Add to PATH (this allows you to use code command in the terminal).
Select the options you prefer and click "Next".
Install:

Review your settings and click "Install" to begin the installation process.
Complete the Installation:

Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the "Launch Visual Studio Code" option.
Click "Finish" to exit the Setup wizard.
After Installation
Open Visual Studio Code:

If you didn't launch VS Code immediately after installation, you can open it from the Start Menu or by double-clicking the desktop icon (if you created one).
Install Extensions (Optional):

Visual Studio Code supports a wide range of extensions to enhance functionality. You can install extensions for languages, debuggers, and tools from the Extensions view (click the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X).
Configure Settings (Optional):

Customize VS Code settings by clicking on the gear icon in the lower left corner and selecting "Settings".
Start Coding:

Open a new file or folder and start coding!


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

heme and Appearance:

Dark/Light Theme: Go to File > Preferences > Color Theme (or press Ctrl+K Ctrl+T) and select a theme that is comfortable for you.


Font Family and Size: Set your preferred font family and size by going to File > Preferences > Settings, then search for font family and font size.
Line Numbers: Enable or adjust line numbers in the editor

Auto Save:
Enable auto save by searching for auto save in settings and setting it to afterDelay or onWindowChange.


Tab Settings:
Configure tab size and whether to use spaces or tabs by searching for tab size and insert spaces in settings.

File Associations:
set file associations to ensure that VS Code recognizes different file types correctly. Go to File > Preferences > Settings and search for files.associations.
Keyboard Shortcuts:

Important Extensions
Language Support:
Python: ms-python.python
JavaScript/TypeScript: ms-vscode.vscode-typescript-next


Code Formatting and Linting:
Prettier - Code formatter: esbenp.prettier-vscode
ESLint: dbaeumer.

vscode-eslint

GitLens: eamodio.gitlens - Provides advanced Git capabilities and insights.

Docker:
Docker: ms-azuretools.vscode-docker
Live Server:

Live Server: ritwickdey.liveserver - Launches a development local server with live reload feature for static & dynamic pages.


Debugger for Chrome: msjsdiag.debugger-for-chrome - Debug your JavaScript code in the Chrome browser.
Remote Development:



After installing Visual Studio Code (VS Code), there are several initial configurations and settings adjustament one has to consider


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.



visual studio have many of the user interfac designed to navigate , here are some of the components of the vs code user interface;

1  ACTIVITY BAR
It provides access to different views and activities in VS Code. Each icon on the Activity Bar represents a different view, such as the Explorer, Search, Source Control, Run and Debug, and Extensions. it is comprise Run, extensions, source,Search, control and Explorer

2 SIDE BAR
It displays the content related to the view selected in the Activity Bar. For example, if the Explorer icon is selected in the Activity Bar, the Side Bar will show the file explorer.

EDITOR GROUP
This is where you open and edit your files. You can open multiple files side by side in split views within the Editor Group.


STATUS BAR

It displays important information about the current file and the overall state of VS Code. It provides quick access to various settings and information.
The items displayed in the Status Bar can be interactive, providing shortcuts to change settings or perform actions.











4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The Command Palette in Visual Studio Code (VS Code) is a powerful tool that provides quick access to a wide range of commands and settings without the need to navigate through menus. Accessing the Command Palette is by Pressig Ctrl+Shift+
some of the examples of commo tasks include the ollowing;
RUnning Commands:

Format Document: Automatically formats the entire document according to the configured code style.

Navigating Files and Symbols:
Open File, Quickly open a file in the workspace.
Command: File: Open File (also accessible via Ctrl+P for quick file search)


Source Control and Git:

Git glone : Clone a Git repository from a URL.
Command: Git: Clone
Git comit : Commit changes to the repository with a message.

Debugging:

Start Debugging: Starts the debugging process based on the launch configuration.
Command: Debug: Start Debugging

Extensions:

Install Extensions: Search for and install new extensions.
Command: Extensions: Install Extensions

Customization and Settings:

Change Color Theme: Switches the color theme of the editor.
Command: Preferences: Color Theme



5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions play a crucial role in Visual Studio Code (VS Code) by enhancing its functionality and customizing it to fit specific development needs.

   Finding Extensions
Marketplace: Extensions can be found in the VS Code Marketplace. You can browse and search for extensions directly from the VS Code interface.

Installing Extensions.
Search for the extension you want to install by typing its name or a related keyword.

Managing Extensions
View Installed Extensions:
Open the Extensions view (Ctrl+Shift+X).
The "Installed" section lists all the extensions currently installed.
Disable or Enable Extensions:
In the Extensions view, find the extension you want to disable or enable.

Uninstall Extensions:
Find the extension you wish to remove in the Extensions view.

Essential Extensions for Web Development
Language Support:
HTML CSS Support (ecmel.vscode-html-css): Provides CSS class name completion for HTML and supports related file features.

Framework and Library Support:
A
GitHub Pull Requests and Issues (GitHub.vscode-pull-request-github): Allows you to manage GitHub pull requests and issues directly within VS Code.

Productivity Tools:

Debugger for Chrome (msjsdiag.debugger-for-chrome): Debug JavaScript code in Google Chrome directly from VS Code.




6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   There are several ways to open the integrated terminal in VS Code:

Keyboard Shortcut:
Press Ctrl+` to toggle the terminal

Command Palette:

Open the Command Palette by pressing Ctrl+Shift+P .
Type Terminal: Create New Integrated Terminal and press E

Menu Bar:
go to View in the menu bar.
Select Terminal from the dropdown menu.
Activity Bar:
Click on the terminal icon in the Activity Bar on the side of the window, if available.

Using the Integrated Terminal

Once the terminal is open, you can perform various tasks as you would in any other terminal:

Running Commands:

You can execute any command-line tool or script, such as npm install, git status, python myscript.py, etc.


You can open multiple terminals by clicking the + icon in the terminal panel or using the command Terminal: Create New Integrated Terminal from the Command Palette.







Splitting Terminals:

Split the terminal pane by clicking the split icon (a small square with a vertical line) next to the + icon. This allows you to view and interact with multiple terminals side by side.

Customizing the Terminal:

You can customize the terminal's appearance and behavior by modifying the settings. Go to File > Preferences > Settings and search for terminal to find options such as font size, shell path, and theme.

Advantages of Using the Integrated Terminal

Seamless Workflow:

The integrated terminal allows you to run commands and view outputs without leaving the editor, making it easier to maintain focus and context while coding.


Context Awareness:
The terminal opens in the context of your workspace or project folder by default, reducing the need to navigate directories manually.

Synchronization with VS Code:
Many VS Code extensions integrate with the terminal, providing enhanced functionality such as debugging, linting, and testing directly within the editor.

Quick Access
You can quickly open and switch between terminals using keyboard shortcuts, making it more efficient than switching between an external terminal application and the editor.

Customization:
The integrated terminal can be customized to fit your preferences, such as changing the shell (e.g., PowerShell, Command Prompt, Git Bash) and adjusting the appearance.







7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating a New File:

Keyboard Shortcut: Press Ctrl+N  to create a new untitled file
Quick Open folder: Press Ctrl+P start typing the name of the file, and select it from the list that appears.

Managing Files and Folders
Explorer Context Menu: Right-click on the file or folder and select Rename, then enter the new name.

Explorer View:

Use the Explorer view to navigate the directory structure of your project. It provides a tree view of your workspace, making it easy to locate and open files and folders.
Quick Open:

Press Ctrl+P  to quickly search for and open files by typing part of their name. 

Press F12 to go to the definition of a symbol
Go to File:

Press Ctrl+P  and type # followed by the symbol name to navigate to a specific symbol in the workspace.

The breadcrumb trail at the top of the editor provides a hierarchical path of the current file’s location. Click on any part of the breadcrumb to navigate to that folder .




8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Seting can be modified  globally by Opening  the Settings UI by clicking on the gear icon in the lower-left corner and selecting Setting
   
   Changing Theme 
   In the search bar at the top, type theme.
Under Preferences, click on Color Theme.
Select a theme from the list. VS Code comes with several built-in themes, and you can also install additional themes from the Extensions Marketplace.

Changing the Font Size


Open the Settings UI.
In the search bar, type font size.
Under Text Editor, find the Font Size setting.
Adjust the value to your preferred font size ie changing from 12 to 15

Customizing Keybindings  
Open the Keybindings UI by going to File > Preferences > Keyboard Shortcuts or by pressing Ctrl+K ,Ctrl+S.
In the search bar, type the command you want to rebind (e.g., copy for the Copy command).
Click on the pencil icon next to the command you want to change.
Press the new key combination you want to assign and press Enter.






9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code? The following are the steps  of setting up and Debugging:
    (1)  ISTALL NECESSARY EXTENSION.
   ensure you have the necessary extension installed is more important.
   (2) Open or create your project
   open vs code , open your files  and create a file 

   (3) Write your code , Write  simple test debugging >
   (4) Configure debugging  by opening the debug panel ad also creating a debug configuration
   (5) Set breakepoints , open the source code file if you want to deburg ie "aoo.py"
   (6) Start debugger  the debugger will start, and execution will pause at breakpoints. You can inspect variables, step through code, and evaluate expressions.

   KEY DEBUGGING FEATURES IN VS CODE 
  12 Breakpoints:This sets breakpoints to pause execution at specific lines
  2  Step Through Code :excute the next line of code but do not step into functions 
Step into the function call to debug inside it (F11).
 Step out of the current function and pause after it returns.
 3 Variable ispection View variables in the Variables pane.
Hover over variables in the source code to see their current values.
4 watch expressions, and the call stack, provide a comprehensive and powerful debugging experience that helps you understand and troubleshoot your code effectively.






10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Integrating Git with Vs code involves initializing a repository , making commints , and  pushing  changing to Github, the process includes
    . Installinf and Verifying git, ensure the Git is installed on the system  by putting git --command 
    Initializing  a respository using "git init" or "git clone"
    Making commits  changes is another process , this ensure  there is staging changes in the source control panel
    writting commit messages and committing staged changes
    .Pushing changes  to git hub Go to GitHub and create a new repository. Copy the repository URL.These steps help manage your project's version control seamlessly within VS Code, enhancing your development workflow

:
 
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

