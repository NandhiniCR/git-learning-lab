# git-learning-lab
"A clean and complete reference of essential Git commands, organized by category with clear explanations for beginners and professionals."    
NOTE:- short, professional, and strong.

Let's Start

Git commands are not infinte. They fall into 10 main categories.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. SETUP AND CONFIGURATION COMMANDS
   
   A) git --version
   
      Explanation: Shows the version of Git installed on your computer Helps you confirm Git installed and check which version you're running.
    
   B) git config -- global user.name
   
      Explanation: Sets your Git username for all repositories on your system. Example: git config -- global user.name "John Doe". Git attaches this name to your         commits so others can see who made the changes.
   
   C) git config -- global user.email
   
      Explanation: Sets your email address for all Git repositories. Example: git config --global user.email "john@example.com" Your email gets attached to your          commits and identifies you on platforms like GitHub.
   
   D) git config --list
   
      Explanation: Displays all Git configuration settings such as username, email, and editor. Useful for verifying that your Git setup is correct.
   
   E) git help
   
      Explanation: Opens the general Git help documentation. It provides a list of Git commands and guides on how to use them.
   
   F) git help <command>
   
      Explanation: Shows detailed help for a specific Git command. Ex: git help commit. helps you understand what the command does, its options, and how to use it.
 ------------------------------------------------------------------------------------------------------------------------------------------------------------------
 2. REPOSITORY CREATION COMMANDS
    
    A) git init
    
    Explanation: Initializes a new empty Git repository in the current directory, allowing you to start tracking changes and version history.

    B) git clone <url>
    
    Explanation: Creates a local copy of a remote repository using its URL. This allows you to work on an existing project and synchronize changes.
    
    C) git init -b main
    
     Explanation: Initializes a repository with the default branch set to main, instead of older defaults like master

    D) git clone --branch <branch>
    
    Explanation: Clones a repository and checks out a specific branch. Example: git clone --branch dev <url>. Useful when you want to work on a particular branch        instead of the default.

    E) git clone --depth 1 <url>
    
    Explanation: Creates a shallow clone containing only the latest commit. Useful for faster cloning and reduced storage when full history isn’t needed.

    F) git init --bare
    
    Explanation: Creates a repository without a working directory—only the version history. Commonly used to set up a central shared remote repository.
    
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------
  3. FILE TRACKING AND STAGING COMMANDS
     
     A) git add <file>
     
     Explanation: Adds a specific file to the staging area so it will be included in the next commit. Useful for selecting which changes to commit.
    
     B) git add .
     
     Explanation: Stages all modified, new, and deleted files in the current directory. Useful for preparing all changes at once.

     C) git rm <file>
     
     Explanation: Removes a file from the working directory and from Git tracking. Use it when you want to permanently delete a file from the repository.

     D) git rm --cached <file>
     
     Explanation: Removes a file from Git tracking but keeps it in your local system. Useful for untracking files like config or environment files.
    
     E) git mv <old> <new>
     
     Explanation: Renames or moves a file and automatically stages the change where this ensures Git correctly tracks the file’s history even after being renamed        or relocated.

     F) git restore --staged <file>
     
     Explanation: Unstages a file without changing its actual content. Useful if you accidentally added a file to the staging area.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------  
