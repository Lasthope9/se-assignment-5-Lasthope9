[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290535&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   1.1 Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - Virtual Studio Code can be only downloaded from the official website: https://code.visualstudio.com/
   - The downloaded software.exe can be placed anywhere in the local machine folder but the default is the "Download Folder" or "C:\Users\YourUsername\Downloads".
   - Run the software as administrator to give it full functionality during the installation process.
   - Then everything will be set as a default, such as creating an environmental path the user needs to press next, until reaching the final part of the installation, also click the "create desktop icon" checkbox for easy access.

2. First-time Setup:
   2.1 After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   - configuration and settings are default after opening Vs-Code, but before any coding happens some extensions must be installed,
   - Auto closing Tag- automatically add a closing tag for you, save time, and reduce errors.
   - Auto Renaming Tag- in HTML/XML when tags are renamed, it auto renames the tag to save time.
   - Bracket Pair Colonizer- identify and make brackets especially when it is time to nest code.
   - Prettier- format the code in a way that anyone can understand and be able to read the code.
   -  ESLint- for Js and Ts, it provides real-time code analysis and adheres users to standards and practices.
   -  Debugger for Chrome- enables Javascript code to debug in Chrome from VScode directly.
   -  Liver Server- Eject your code to Chrome for preview before deploying. 
   -  Code Spell Checker- checks for errors in the code to help improve comments and overall quality. 
  

4. User Interface Overview:
   4.1 Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   - The Activity bar is positioned on the left side of the VScode, providing different access to features, such as Explorer, Search, Source Control, Debug, and Extensions.
   - Side Bar serves the same purpose as the Activity bar, but stores features that are related to your workspace, and the project that you are handling.
   - Editor Group contains more than one panel where the developer can view and edit the code.
   - The status bar, is located at the bottom line of Vscode, showing information related to the current working workspace of the developer, like Git status, Live-share, and a few notifications. 
   

6. Command Palette:
   6.1 What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   - Powerful text-based interface that provides a simple way to navigate through Vscode without the use of a mouse, I can easily access it by pressing "Ctrl + Shift + P", and a common task that is used is to toggle terminal or fast way to get Git status.

7. Extensions in VS Code:
   7.1 Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   - Extensions in VS-code function as a mini-package feature compressed to perform specific tasks after being installed in the VScode, extensions are located at the side-bar, an icon of the box like the top of each other, and one falls out, you press the icon and two 
     sections will be available (Installed and Recommended), verified extensions will appear or search for the desired extension, extensions for web development are Live Server, Prettier, HTML CSS Support, Auto Renaming and Closing Tags, ESlint, Brackets Pair Colonizer, 
     Path Intellisense and Javascript Code Snippet  

8. Integrated Terminal:
   8.1 Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   - The are many ways to open the integrated terminal in VS Code, I can press "View" at the top and scroll to "Terminal" or I can open it through the command palette "Ctrl + Shift + P" and toggle to integrated Terminal.
   - Integrated Terminal has many uses such as installing managing packages directly like Pip, npm, or yarm, or having access to Git via the terminal.
   - Integrated Terminal is customizable to any like of the developer and has features of the VS Code than the external Terminal. 

10. File and Folder Management:
   10.1 Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   - files can be created through Explorer view, on the side-bar, the first icon that looks like paper, or through a shortcut "Ctrol + Shift + N", after the folder will show spacing to be able to rename it to any desired name, or I can just right-click on top of the 
     file and scroll until I find the section "Rename", managing the folders can be tricky or simple, but the most common is to just right-click and a few options like "Rename", and "Delete" will be visible, and to move the folder, press "left-click" on the mouse, hold 
     it and drag the folder to any destination within the Explorer view.

11. Settings and Preferences:
   11.1 Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
    - VS code allows users to be flexible, users can change settings and preferences through the setting Ul(⚙️) or using the Setting.json file via the integrated terminal
    - To change the theme, through settings(⚙️), click on "color theme", and choose the desire from the pool provided by VS Code.
    - To change font size, through settings(⚙️), search for "font", and choose the desired font.
    - To change keybinding, through settings(⚙️), search for "keybinding", and select the desire.
    - All three also have alternative ways to change through the Settings.Json File via Integrated Terminal.

11. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   - Depending on the language that the developer is using to code, some debug is already installed e.g if you use Python there will be an icon (▶️) at the top to debug but in other languages like Javascript, you have to install an extension called "Debugger for 
     Chrome", and probably other coding languages too, to set up, you have to open your project folder in VS Code, click on the Debug icon (🛠️) in the Activity Bar on the side of the window, click on the gear icon (⚙️) that says "No Configurations" to create a 
     launch.json file, select the environment you want to debug in (e.g., Node.js, Chrome), and VS Code will generate a launch.json file with a basic configuration for debugging in that environment. You may need to customize it according to your project setup.
  - features available are Variable inspections, step-through code, breakpoint action, and a few.

11. Using Source Control:
    11.1 How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    - Open the project folder in VS Code, Go to Source Control by clicking on the 📂 in the Activity Bar or Ctrl + Shift + G (Windows/Linux) or Cmd + Shift + G (macOS)
    - In the Source Control view you’ll see a list of changes to your files. Click on a file and then the + to stage that file or click the + at the top to stage all.
    - Once you’ve made your changes enter a commit message in the top box and press "Enter"
    - If you haven’t already, create a new repo on GitHub and copy the url. Then link your local repo to it.
    - In VS Code, open Terminal (⌃) and run git remote add e.g. git remote add origin <repository_url>
    - Replace <repository_url> with the URL of your GitHub repository.
    - After adding the remote repository, you can push your changes to GitHub using the git push command e.g. "git push -u origin master".
    - This will push to origin/master. If you’re on a different branch, replace master.
      

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

