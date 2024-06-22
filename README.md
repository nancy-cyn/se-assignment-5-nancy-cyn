[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15310146&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

## 1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.


* ##### Prerequisites
   * Windows 11 operating system.
   * Administrator access to install software on your computer.
   * Internet connection to download VS Code.

* ##### Steps to Download and Install VS Code
   * _Visit the Visual Studio Code Download Page:_ Open your web browser and go to the [Visual Studio Code download page.](https://code.visualstudio.com/Download)
![Image of Visual Studio Code download page](/Screenshots/Screenshot%202024-06-19%20101704.png)
   * _Download Visual Studio Code:_ Choose the appropriate download link for your operating system (e.g., Windows, macOS, or Linux). In my case I had choose Windows.
   * _Run the installer:_ Double-click the .exe file you downloaded. If prompted by User Account Control (UAC), click "Yes" to allow the installation.
   * _Follow the Installation Prompts_
      * Agree to the license terms: Read the license agreement, check the box to accept the agreement, and click "Next".
      * Select the destination folder: Choose the folder where Visual Studio Code will be installed or use the default location. Click "Next".
   * Select additional tasks:
      * Check "Create a desktop icon" if you want a shortcut on your desktop.
      * Check "Add to PATH" if you want to be able to open VS Code from the command line.
      * Check "Add Open with Code action to Windows Explorer file context menu".
      * Check "Add Open with Code action to Windows Explorer directory context menu".
      * Click "Next".
      * Install: Click "Install" to start the installation process.
      * Finish the installation: Once the installation is complete, check "Launch Visual Studio Code" and click "Finish" to open VS Code.


## 2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

      * Such as Python to develop Python projects.
         ![Image of Python extension page ](/Screenshots/Screenshot%202024-06-19%20123652.png)
      * Such as Dart to develop Dart projects.
         ![Image of Dart extension page ](/Screenshots/Screenshot%202024-06-19%20124412.png)
      * Such as Markdown Preview Enhanced to view README files before they are pushed to github
         ![Image of Dart extension page ](/Screenshots/Screenshot%202024-06-19%20124608.png)
      * Prettier to help format my code
         ![Image of Prettier extension page ](/Screenshots/Screenshot%202024-06-19%20123740.png)


## 3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   ![Image of VS user interface ](/Screenshots/Screenshot%202024-06-22%20110843.png)
      * _Activity Bar (RED):_ It provides quick access to different views or sections of the IDE or editor, such as file navigation, search functionality, version control, debugging, and extensions. Each icon or tab in the Activity Bar represents a specific set of tools or functionality related to managing and developing projects.

      * _Side Bar (GREEN):_ It typically displays a tree view of the project's folder structure, allowing developers to browse files and directories, open files for editing, manage source control (like Git), and interact with various project-related tools and settings. It provides a more granular view and control over the project's files compared to the Activity Bar's higher-level navigation.

      * _Editor Group (ORANGE):_ This feature is particularly useful for multitasking, enabling developers to work on different files or even different parts of the same file simultaneously. Each Editor Group can contain one or more editor tabs, allowing for efficient code editing and referencing across different contexts.

      * _Status Bar (BLUE):_ It often displays information such as the current line and column number, indentation settings, language mode or file type, encoding format, and sometimes additional information like Git branch status or debugging output. The Status Bar may also include interactive elements for toggling settings or accessing specific features quickly.

## 4. Command Palette:
   - What is the Command Palette in VS Code: The Command Palette in VS Code acts as a central hub for accessing all functionalities and settings within the editor.  It's a powerful tool that  helps you quickly find and execute commands without navigating through menus.
   - How can it be accessed? Go to Menu: Navigate to the View menu and select Command Palette.
   - Provide examples of common tasks that can be performed using the Command Palette.
      - Open Files and Folders: Quickly navigate to specific files or folders within your project by typing their name or path.
      - Search and Replace: Use commands like "Find" or "Replace" to search for text across your codebase.
      - Code Formatting: Find commands like "Format Document" or use extensions that provide formatting options.
      - Refactoring: Many extensions offer refactoring commands to reorganize or restructure your code.
      - Terminal: Access the integrated terminal by searching for "Terminal".
      - Settings: Search for specific settings you want to adjust, like "Font Size" or "Indent using Spaces".
      - Install Extensions: Find the "Extensions" command to open the extensions marketplace and install new tools.

## 5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code.
      - Enhancing Functionality: Extensions add new features and functionalities to VS Code, such as language support (e.g., Python), debugging tools, version control integration (e.g., Git), code formatting, and more.
      - Customization: Users can customize their editing experience with themes, icons, and keybindings through extensions.
   - How can users find, install, and manage extensions? 
      - Finding Extensions: Open the Command Palette, type Extensions: Install Extensions, and press Enter to search for extensions directly within VS Code.
      - Installing Extensions: Search for an extension, select it, and click Install.
      - Managing Extensions: Go to the Extensions view in VS Code. From here, you can enable, disable, or uninstall extensions.
   - Provide examples of essential extensions for web development.
      - Debugger for Chrome: Allows debugging JavaScript code running in the Google Chrome browser directly from VS Code.
      - Prettier: Automatically formats code to ensure consistent styling across your project.

## 6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code.
      - Opening: Go to the Terminal menu and select New Terminal.
      - Using: The integrated terminal behaves like a regular terminal where you can execute commands specific to your operating system.  
   - What are the advantages of using the integrated terminal compared to an external terminal?
      - The integrated terminal is tightly integrated into the VS Code interface, allowing you to work within the same window without switching between applications. This integration enhances productivity by reducing context switching.
      - The integrated terminal opens at the root of your current workspace or project directory by default. This ensures that terminal commands operate within the correct context, making it easier to manage project-specific tasks and workflows.


## 7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. 
      - Creating a New File/Folder: Right-click in the Explorer view (Side Bar) and select New File/NewFolder. Enter the file/folder name.
      - Opening Files: Double-click on a file in the Explorer view to open it in the editor.
      - Managing Files and Folders:
         - Renaming Files and Folders: Right-click on a file or folder in the Explorer view and select Rename, or press F2. Enter the new name and press Enter.
         - Deleting Files and Folders: Right-click on a file or folder in the Explorer view and select Delete, or press Delete key. Confirm the deletion if prompted.
         - Moving Files and Folders: Drag and drop files or folders within the Explorer view to rearrange them or move them to different directories.
   - How can users navigate between different files and directories efficiently? 
      - Using the Explorer View (Side Bar):The Explorer view provides a tree view of your project's folder structure. You can collapse or expand directories to navigate through different levels.
      - Using Tabs: Each file opened in VS Code appears as a tab in the editor area. Click on a tab to switch between open files quickly.

## 8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
      * _Interface Theme:_ VS Code offers a variety of themes for the editor interface. Choose a theme that's easy on your eyes and promotes focus. Which can be found under workbench settings
       ![Image of Visual Studio Code workbench settings](/Screenshots/Screenshot%202024-06-22%20105345.png)
      * _Font Size and Style:_ Adjust the font size and style to your preference for better readability. This can also be found in the Settings editor. Which can be found in text editor settings
      ![Image of Visual Studio Code text editor settings](/Screenshots/Screenshot%202024-06-22%20105455.png)

##  9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code.
      - Start Debugging: Press F5 or click the green play button (Start Debugging) in the Run view to start debugging. VS Code will launch your program in debug mode according to your configured launch settings.
   - What are some key debugging features available in VS Code?
      - Watch Expressions: Monitor the value of expressions and variables continuously during debugging.
      - Debug Console: Interact with your program by executing commands, evaluating expressions, or printing debug information.

## 10. Using Source Control:

   - How can users integrate Git with VS Code for version control? 
      - Before using Git with VS Code, ensure that Git is installed on your system.
      - Set Git Bash as your default terminal
   - Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
      - Open the terminal
      - Initialize a Git Repository write:

               git init
      - Stage and Commit Changes

               git add .
               git commit -m "First git project"
      - Push Changes to GitHub

               git push




 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

