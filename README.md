[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Stud- Discuss the role of extensions in VS Code.io Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244466&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS CodeInstructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Steps involved:-open your browser(chrome in my case),navigate to official vs code website,select downloads for windows 11,locate the location of the downloaded file,double click to open it for installation process.Read the licence agreement,accept the agreement and click next,choose installation location and click next,select additional tasks or recommended options which include;add to path,create a desktop icon.make your selections and click next,review your setup and click install,After installation is complete ,choose to launch vs code and the click finish.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing vs code,there are several intial configurations and settings you should adjust for optimal environment,they includes,
   (a) install essential extensions which include language support,version control and productivity tools.
   (b) Configure settings which include,prettier configure,auto save,tab size,word wrap,line numbers and font size and family.
   (c) Terminal configuration:-configure the integrated terminal to use prefered shell.
   (d) Git configuration to enable Git integration.
   (e) Backup and sync:-use settings sync to back up and synchronize settings across different machines.
   (f) Keybindings:-Customize keybindings to fit the workflow.


3. User Interface Overview:
 Explain the main components of the VS Code user interface. 
Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   (a) Activity Bar,it allows to switch between various views and features which include;Explorer,search,source control,run and debug and extensions.
   (b) Side bar which displays different views depending on the icon selected in the activity Bar.
   (c) Editors Group;its the main area where you write and edit code.
   (d) Status Bar provides useful information about the current state of the workspace and the open file.
   

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

What is the Command Palette in VS Code.
Its a powerful tool that allows users to access and execute various commands and settings within the editor through a searchable interface.

It can be accessed by pressing ctrl,shift then p on the keyboard or view menu in the top menu bar and select command palette.

Common tasks perfomed using command palette includes;
(a) Opening files and folders
(b) Running commands such as savings files
(c) Searching and navigating code such as searching for symboys of files.
(d) Configuring settings
(e) Running tasks such as build scripts

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions in VS Code:These are additional features and functionalities that enhance the editors capabilities.

Discuss the role of extensions in VS Code:-
They play a key role in extending functionality,language support,productivity,customization and integrations of vs code,allowing it to be versatile and powerful editor for developers across different programming languages and workflows.

How can users find, install, and manage extensions?
Click on the extensions icon in the activity bar on the side of the VS Code of press ctrl+shift+ x to open the extensions view;once you find the one you like to install,click on the install button next to extensions bar(...), after installation the button changes to manage button which allows you to updates,uninstill and disable extensions.

Provide examples of essential extensions for web development.
(a) Gitlens:-Enhances the built in git functionality in vs code
(b) CSS Peek:-Allows to navigate from HTML to CSS and Sass class definations directlywithin your code.
(c) Path Intellisense:-Autocompletes file paths and filenamesin import statements.
(d) Debugger for chrome:-Allows you to debug javascript code running in the google chrome browser directly from VS code.
(e) Prettier:-integrates the prettier code formatter into VS code.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

    Describe how to open and use the integrated terminal in VS Code.

    Open VS code and launch visual code on laptop.
    Open the project folder you want to work on vs code.Go to file,open folder and navigates to folder you require and select the file to work on.open the integrated terminal,New terminal,use git bash and enter to run commands.
    eg git add . 
       git commit_m "Answered Assignment 5"
       git push and confirm to github.

       What are the advantages of using the integrated terminal compared to an external terminal?

       1. it provides convenient access to output and error messages generated by your commands.
       2. it can be customized to suit your preferences.
       3. its easier to configure and execute tasks like bulid scripts directly from the terminal.
       4. its more convenience to access the integrated terminal with a simple keyboard shortcut.
       5. it is seamlessly integrated into the VS Code interface allowing to perform tasks like running command.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creatings Files:-To create new file,use the file menu  and select New File or use the shortcut ctrl+N

   Creatings new folder:-right click in the Explorer pane ,select New folder and then give it a name.

   OPening Files and Folders:To open an existing file,Go to file menu and select 'Open File' or ctrl+o to open Folder ,use the file menu and select Open Folder or use shortcut ctrl+k ctrl +o

   Managing files and folders in vs code:-Renaming files and folders, Right click on the folder or file in the Explorer pane and select"Rename or press f2.

   Deleting:-Right click on the file or folder and select Delete.

   Coping or Moving file and folders:-Drag and drop files and folders within the Explorer pane to move them.

   Cut and Paste use ctrl+x to cut and then navigate to the desired location and use ctrl +v to paste.

   Search and Replace files:- use ctrl+shift+F to open the search pane and search acrossfiles.Use the replace functionality within the search pane to find and replace text across multiple files.

   How can users navigate between different files and directories efficiently?:-To navigates around your projects files and directories in vs code more efficiently ,the following techniques are applied;
   (a) Quick open ,press ctrl+p to bring up the Quick Open dialog and start typing name of the file you want to open.
   (b) Command palette:-press ctrl+shift+p to open the command palette.
   (c) Keyboard Shortcuts:- Go to file use ctrl+p to quickly open file
   (d) Tabs and Editors:-Switch between open files,use ctrl+Tab to switch between open files.Split Editor use ctrl+\ to split the editor and view multiple files side by side.
   (e) Search and Replace:- search across files use ctrl+shift+f to search a text across files,find in file use ctrl+f to find text within the current file.Replace in file use ctrl+H to find and replace text within the current file.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code?:-
   Users can find and customize settings in vs code through the following methods;using the settings GUI,modifying the settings .json file directly and accessing workspace.
   
    Provide examples of how to change the theme, font size, and keybindings.

(a) Changing the theme ,open the command palette by pressing(ctrl+shift+p in windows and linux) or cmd+shift+p in macOS.Type preferences and select colour theme.
(b) Font Size;open the settings GUI by pressing ctrl+,search for font size in the search bar at the top and adjust font size settings to your desired value.
(c) Keybindings;use the shortcut keys by pressing ctrl+shift+p in windows or press md+shift+p in macOS,type preference and search for command and change its keybindings by clicking on the pencil icon next to the command.

9. Debugging in VS Code:
it refers to the process of identifying and fixing erors in you code.

Outline the steps to set up and start debugging a simple program in VS Code.
   it involves several key steps,they includes;
   (a) install vs code and required extensions
   (b) open or create your project
   (c) write a simple programe
   (d) configure the Debugger
   (e) customize 
   (f) set breakpoints
   (g) start debugging
   (h) use the debug console
   (i) stop debugging

    What are some key debugging features available in VS Code?

    (a) Breakpoints
    (b) watch variables
    (c) call stack
    (d) variable and scope
    (e) Debug console
    (f) Step controls
    (g) Exception Handlings
    (h) Inline values
    (i) Logpoints
    (k) Debugging multiple threads and processes.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? 
    integrating Git with vs code follows the following steps;
    (a) set up Git in VS Code,Go to extensions view by clicking the extensions icon in the activity bar on windows or by pressing ctrl+shift+x,search for the Git hub pull request and issues extension and install it
    (b) Configure Git in vs code by clone and selecting it then select the location to save the respository.


    Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Process involved;
Create a new Git respository ,open a folder in vs code,press ctrl+shift+G ,click the intialize respository button.
In the source control view,type  a commit message in the input inbox at top then click the checkmark icon to commit your changes.
Select the source control view then select push.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.

references;
Journals
Class works
Documentaries
Magazines