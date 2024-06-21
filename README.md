[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15310893&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

*Visual Studio code is a source code editor that supports Java,Javascripts,python,Node j.s and other programming languages
downloading and installing Visual studio code on windows 11 requires the following steps;
-visit the visual studio website and click on "Download Visual Studio"
-Download process will start
-run the installer
-choose the "Visual Studio" workload during installation, which includes the necessary components for general development
-select workloads and components:
-in the visual studio installer, select the workloads and components you need based on your dvelopment requirements, common workloads include "web development"
-modify installation
-if needed, you can customize the installation by clicking on the "individual components" tab in the installer and selecting or deselecting specific components.
-this may take sometime as it involves downloading and installing the selected componens.
-Launch Visual Studio:
-Once the installation is complete, launch visual studio
-On the welcome screen, select your development environment. forexample you can choose "development settings" based on your preferred coding style
-Start coding:
you are now ready to start coding, thus create a new project.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

Once you have installed and set up VS Code, these initial configurations and settings should be adjusted for an optimal coding environment
(i) User Interface-a quick orientation to VS Code
(ii) Basic Editing- learn about the powerful VS Code editor
(iii) Code Navigation- move quickly through your source code
(iv) Debugging- debug your source code directly in the VS Code editor
(v)Proxy Server Support- configure your proxy settings


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

(i) EDITOR- the main area to edit your files. you can open as many editors as you like side by side vertically and horizontally.
(ii) PRIMARY SIDE BAR- contains different views like the explorer to assist you while working on your project
(iii) STATUS BAR- information about the opened project and the files you edit.
(iv) ACTIVITY BAR- located on the far left-hand side. lets you switch between views na dgives additional context-specific indicators, like the number of outgoing changes when Git is enabled. you can change the position of the activity bar.
(v) PANEL- An additional space for views below the editor region. by default, it contains output,debug information,errors and warnings, and an intergrated terminal. the panel can also be moved to the left or right for more vertical space.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
*Command Palette is a powerful interface element that allows users to perform actions more efficiently by typing commands also used by extensions to expose functionality to users, bind to actions in VS Code's UI and implement internal logic.

*Command Palette can be assessed by various ways like tapping control+shift+P (Wndows/Linux).
Examples of common tasks that can be performed using command palette
a command palette is available in every Jetbrains solution, forexample, in Pycharm/Webstorm/Datagrip by pressing "shift" twice.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions play several roles in VS Code as follows
*by letting you add languages
*acts as debuggers
*acts as tools to your installation to support your development workflow

For one to install an extension, select the install button. once the installation is complete, the install button will change to the manage gear button.
to find for an extension, one can clear the search box at the top of the extensions view and type in the name of the extension, tool or programming language you're looking for.
for one to manage extensions, he can install, disbale, update and uninstall extensions through the extensions view, command palette or command line switches.
examples for extensions for web development are Clear Cache Chrome extension, CollorZilla, WhatFont Chrome Extension.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   *You can open and use the intergrated terminal in VS Code by using keyboard shortcut,command palette or using the menu.
   By using the menu bar on windows 10/11 and navigate the menu bar at the top, from there,select the "view'option and the then click on "terminal"and once the terminal window appears you can start using it to run commands and scripts in various languages such as bash,python,Java.

 
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
*PROCEDURES
(i) Open the VS Code project containing your application.
(ii) Click the "create file" on the status bar on the bottom of the VS Code IDE
You can also use a keyboard shortcut i.e Control+shift+P on windows
(iii) Select the file group from the select file group list
(iv) select the file type from the select type list from the command palette at the top of the screen
(v) enter a name for the file in the create new file dialog box.
the extensions creates a file in your application on your local file system. the new file is added to your instance when you synchronize your workspace.

*HOW TO CHANGE DIRECTORIES IN COMMAND PROMPT
(i) type cd and then press space
(ii) drag and drop the folder you want to browse into the window. forexample,if we drag the downloads folder,the prompt might say this
cd C:\Users\name\Downloads
(iii) press enter to change the working directory to that folder

*HOW DO I NAVIGATE TO A FOLDER IN COMMAND PROMPT?
(i) type cd followed by a space, then type the folder's name. in this exmaple,the change directory commnand switches from the users folder to the jonfi folder:
cd jonfi
C:\Users>cd jonfi
C:\Users\jonfi>


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

*SETTINGS EDITOR
use the settings editor to review and change VS Code settings. to open the settings editor, navigate to file>preference>settings
when you open the settings editor,you can search and discover the settings you are looking for. when you search using the search bar, it not only shows and highlights the settings matching your criteria but also filter out those which are not matching.

*HOW TO CHANGE COLOR THEME
(i) open the menu bar,select tools>options
(ii) in the options list select environment>general
(iii) in the color theme list,select either default dark theme,the light theme,the blue theme


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
*HOW TO PERFORM DEBUGGING IN A SIMPLE PROGRAM IN A VS CODE
(i) Review the Code
to debug the code,you should begin by going through the code line by line and try to identify the errors with logic

(ii) Test with sample inputs
make sure you understand the problem clearly before starting to code, construct an algorithm to solve the problem and then start to code

(iii) Dry run the Code
is a technique used by programmers to visualize the execution of a code on paper and understand the logic of the code without actually running it on the computer.

(iv) Review the Algorithmic logic;
by reading the problem statement again and understand the problem statement clearly

(v) Simplify the Code
in order for the code to become easier to code


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 To use git and githuv in VS code,first make sure you have git installed on your computer and then you can sign into VS Code with your github account in the accounts menu in the lower right of the activity bar to enable additional features like settings sync but also cloning and publishing repositories from github.

*PROCESS OF INITIALIZING A REPOSITORY, MAKING COMMITS AND PUSHING CHANGES TO GITHUB
(i) pick an existing or new folder on your computer and open it in VS code
(ii)in the source control view,select the initialize repository button
this creates a new git repository in the current folder,allowing you to start tracking code changes

*MAKING COMMITS
once you have a git repo set up,you can start tracking code changes by staging and commiting your newly created code
you can access the source control view from the activity bar to all changed files in your workspace. you can toggle between a tree view or list view by using the tree/list icon in the source control view header.

*PUSHING CHANGES TO GITHUB
once you have made commits to your local git repository, you can push them to the remote repository. the sync changes button indicates how many commits are going to be pushed and pulled.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

