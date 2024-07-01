[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15295226&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

 - Visit the Visual Studio Code download page: [VS Code Download](https://code.visualstudio.com/Download).
  - Select the appropriate version for Windows and download the installer.
- Run the downloaded installer.
 - Follow the installation steps, accepting the license agreement and the installation process.
   - Select additional tasks such as adding to PATH and creating a desktop icon.
  

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Choose a Theme and Font:
   - To select a theme that matches your style, go to `File` > `Preferences` > `Color Theme` (e.g., Dark+, Light+).
   - You can also adjust the font size and family by modifying the `settings.json` file or going to `File` > `Preferences` > `Settings`.
- Open extensions view and install some commonly used extensions such as;
   Prettier
  Python
  Live server
  Git lenSetting Up the Integrated Terminal**:
   - To configure your preferred shell (e.g., PowerShell, Command Prompt, Git Bash), go to `File` > `Preferences` > `Settings` and search for "Terminal".
   - Make sure your code formatting remains consistent by setting up Prettier or another code formatter as the default formatter.
     "editor.defaultFormatter": "esbenp.prettier-vscode",
     "editor.formatOnSave": true
     Enabling Auto-Save:
   - Enable automatic saving of files by adding `"files.autoSave": "afterDelay"` to the `settings.json` file.
-Git Configuration
   - If you use Git, set up your user settings for Git in VS Code. Simply go to the terminal and enter the following commands, replacing "Your Name" and "your.email@example.com" with your own information:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   The user interface of VS Code is designed to make it easy for you to navigate and access different tools and features:

Activity Bar: Gives you quick access to various views.
Side Bar: Shows you content and tools that are related to the activity you've selected.
Editor Group: This is the main workspace where you can edit your files.
Status Bar: Provides you with contextual information and shortcuts.



4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in Visual Studio Code is a tool that gives you access to commands and features all in one place. It enables you 5to quickly perform tasks without digging through menus.How to access the Command Palette
Keyboard Shortcut: Just press Ctrl+Shift+P (or F1).
Menu Access: Go to View > Command Palette.
Common Tasks Performed Using the Command Palette
File Operations:

Open File: Simply start typing "Open File" to quickly open a specific file.
Save All Files: Type "Save All" to save all your open files at once.
Git Commands:

Commit Changes: Type "Git: Commit" to commit your changes with a message.
Push/Pull: Type "Git: Push" or "Git: Pull" to sync up with your remote repository.
Extension Management:

Install Extensions: Type "Extensions: Install" to browse and install cool extensions.
Disable Extensions: Type "Extensions: Disable" to turn off any installed extensions.
Editor Management:

Split Editor: Type "View: Split Editor" to divide your current editor into multiple views.
Toggle Terminal: Type "View: Toggle Terminal" to open or close the built-in terminal.
Run and Debug:

Start Debugging: Type "Debug: Start" to begin debugging your code like a boss.
Run Task: Type "Tasks: Run Task" to run predefined tasks like a pro.
Search and Replace:

Find in Files: Type "Search: Find in Files" to search through all your files in the workspace.
Replace in Files: Type "Search: Replace in Files" to replace text in multiple files.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Role of Extensions in VS Code

Extensions in VS Code play a role in enhancing the functionality of the editor. 
They allow one to add new features, tools and integrations
They customize development environments according to one's needs.
Finding, Installing, and Managing Extensions

1. Finding Extensions:
  - One can get extensions by clicking on the extensions icon in the activity bar or by pressing  `Ctrl+Shift+X` on your keyboard.

2. Installing Extensions:
   - Once you've found the desired extension, simply click on the "Install" button to add it to your VS Code.

3. Managing Extensions:
   - To manage your extensions, you can enable or disable them directly from the Extensions view.

Essential Extensions for Web Development

1. Live Server:
   - Live Server is a must-have extension that launches a local development server with live reload functionality.
   - To install Live Server, simply search for it in the Extensions view.

2. Prettier - Code Formatter:
   - This handy extension automatically formats your code, making it more readable and consistent.
   - To install Prettier, search for it in the Extensions view.

3. ESLint:
   - ESLint is a powerful tool that provides JavaScript and TypeScript linting, helping you catch errors and maintain code quality.
   - To install ESLint, search for it in the Extensions view.

4. Debugger for Chrome:
   - With this extension, you can debug your JavaScript code directly in Google Chrome from within VS Code.
   - To install Debugger for Chrome, search for it in the Extensions view


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   How to Open and Use the Integrated Terminal in VS Code

1. Opening the Integrated Terminal
   - Menu Access: `View` > `Terminal`.
   - Activity Bar: Click the Terminal icon.

2. **Using the Integrated Terminal**:
   - New Terminal: Click the plus (+) icon.
   - Switch Terminals: Use the dropdown menu in the terminal panel.
   - Run Commands: Type and execute commands as in any terminal.
   - Split Terminal: Click the split icon for multiple panes.
   - Customize Shell: Go to `File` > `Preferences` > `Settings` and search for "terminal.integrated.shell".

Advantages of the Integrated Terminal

1. Convenience and Accessibility:
   - Single Interface: Code and terminal in the same window.
   - Workspace Integration: Terminal starts in the project root directory.

2. Enhanced Productivity:
   - Keyboard Shortcuts: Quick access and control.
   - Command Management: Manage and switch between multiple terminals easily.

3. Synchronization:
   - Consistent Environment: Shared environment variables and paths with VS Code.
   - Theming: Customize terminal appearance to match the editor.

4. Integrated Tools:
   - Extensions: Direct integration with task runners, debuggers, and linters.
   - File Access: Drag and drop files for path usage in commands


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating Documents and Directories
In the Explorer View:
New Document: If you want a new file, choose "New File" from the right-click menu in the Explorer view.
New Directory: Using the same right-click menu, you can create a "New Folder" in the Explorer view.
While Using the Command Palette:
New Document: Hit Ctrl+Shift+P and then type "New File" to make a new file, and then click Enter.
New Directory: You should , type in "New Folder", and then click Enter.
Accessing Documents and Directories
How to Use the Explorer View:
To open a file: Just do a double-click on a file present in the Explorer view.
To open a folder: Go to File, choose Open Folder then find and select the folder you want.
How to Use the Command Palette:
To open a file: Hit Ctrl+P, key in the file name, and then press the Enter key.
Opening Files using Drag and Drop:
To open files or folders: Drag any file or folder in your file explorer and let go of it on the VS Code window.
How to Manage Files and Folders
Changing Names:
By Using Explorer View: Locate a file or folder right-click and pick "Rename".
Taking Out:
By Using Explorer View: Locate a file or folder right-click and choose "Delete".
Shifting:
By Drag and Drop: drag your file or folder to where you want it to be in the Explorer view.
Quick Swapping Between Files and Folders.
**Open **:
Instruction: To bring up the Quick Open dialog, hit Ctrl+P then punch in the file's name that you're looking to open.
Finding stuff quick: To locate files put in bits of names (for example, punch in "ind" to get "index.html").
Find a Symbol:
Instruction: To find symbols inside a file (like functions variables), push Ctrl+Shift+O.
Find a Definition:
Instruction: To find where a function or variable is defined right-click on it and choose "Go to Definition" or press F12.
Navigational Breadcrumbs:
Turn on Breadcrumbs: To move through the file setup, tap on the breadcrumbs at the pinnacle of the editing panel.
Tabs for Files:
Flip Tabs: To flip between files that are open, hit the tabs at the summit of the editor or press Ctrl+Tab.
View of Explorer:
Travel: Use the Explorer's vision on the left portion to roam through the layout of the directory.
Built-in Terminal:
Direction on Command Line: Use the built-in terminal to journey and launch files with instructions like cd and code .


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   In VS Code here's how to locate and customize settings:

Go to settings by clicking file, preferences, settings
To alter the theme, go to file the preferences>color theme
To change the font size search font size in settings or modify settings.json.



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   To set up and start debugging in VS Code:
Open your project folder.
Create or open a program file.
Write a simple program.
Set up a debug configuration via launch.json.
Set breakpoints.
Start debugging with F5.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Initializing a Repository
Open Project in VS Code:
Navigate to File > Open Folder and select your project folder.
Initialize Git Repository:
Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl+Shift+G.
Click the "Initialize Repository" button.
Making Commits
Stage Changes:
In the Source Control view, you'll see a list of changes. Click the plus (+) icon next to each file to stage it or click the "Stage All Changes" button.
Commit Changes:
After staging changes, type a commit message in the input box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter to commit the changes.
Pushing Changes to GitHub
Create a Repository on GitHub:
Go to GitHub, log in, and create a new repository. Copy the repository URL.
Add Remote Repository:
In VS Code, open the integrated terminal by pressing Ctrl+ (backtick).
Add the remote repository by running:
sh
Copy code
git remote add origin <repository-url>


Push Changes:
In the terminal, push your commits to GitHub by running:
sh
Copy code

source: class recordings   

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

