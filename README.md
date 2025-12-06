# git-learning-lab
"A clean and complete reference of essential Git commands, organized by category with clear explanations for beginners and professionals."    
NOTE:- short, professional, and strong.

Let's Start
Git commands are not infinte. They fall into 10 main categories.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. SETUP AND CONFIGURATION COMMANDS
   A) git --version
      Explanation: Shows the version of Git installed on your computer aHelps you confirm Git installed and check which version you're running.
    
   B) git config --global user.name
      Explanation: Sets your Git username for all repositories on your machine. Example: git config -- global user.name "John Doe" and Git uses this name to label        your commits so others know who made the changes.
   
   C) git config --global user.email
      Explanation: Sets your email address for all Git repositories. Example: git config --global user.email "john@example.com" Your email gets attached to your          commits and identifies you on platforms like GitHub.
   
   D) git config --list
      Explanation: Displays all Git configuration settings, including username, email, editor, etc. So that it lets you verify that your Git settings are correct.
   
   E) git help
      Explanation: Opens the general Git help documentation where it provides you a list of Git commands and guides for using Git.
   
   F) git help <command>
      Explanation: Shows detailed help for a specific Git command. Ex:git help commit helps you understand what the command does, its options, and how to use it.
 ------------------------------------------------------------------------------------------------------------------------------------------------------------------
 2. REPOSITORY CREATION COMMANDS
    A) git init
    Explanation: Initializes a new empty Git repository in the current directory and allows you to start tracking file changes and version history locally.

    B) git clone <url>
    Explanation: Creates a local copy of a remote repository using its URL.This lets you work on an existing project and pull/push changes.

    C) git init -b main
     Explanation: Initializes a new Git repository with the default branch named main it is useful when you want your project to start with a modern, standard           branch name instead of older defaults like master.

    D) git clone --branch <branch>
    Explanation: Clones a repository and directly checks out the specific branch you choose.This is helpful when you don't want the default branch but a particular     feature or development branch.

    E) git clone --depth 1 <url>
    Explanation: Creates a shallow clone with only the latest commit from the repository for reducing download time and saving storage when you only need the most      recent version of the code.

    F) git init --bare
    Explanation: Creates a Git repository without a working directory—just the version control data wherethis is commonly used to set up a central or shared remote     repository for collaboration.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------   3. FILE TRACKING AND STAGING COMMANDS
     A) git add <file>
     Explanation: Adds the specified file to the staging area so its changes are prepared to be included in the next commit where this is useful for selecting           exactly which files you want to record in your commit.
    
     B) git add .
     Explanation: Stages all modified, new, or deleted files in the current directory where this helps quickly prepare every change in the project for committing        without selecting files one by one.

     C) git rm <file>
     Explanation: Deletes the file from both your working directory and the Git repository where this is used when you want to permanently remove a file from the        project’s tracked content.

     D) git rm --cached <file>
     Explanation: Removes the file from Git’s tracking but leaves it untouched on your system where this is useful for keeping a file locally (like config files)        without including it in the repository.
    
     E) git mv <old> <new>
     Explanation: Renames or moves a file and automatically stages the change where this ensures Git correctly tracks the file’s history even after being renamed        or relocated.

     F) git restore --staged <file>
     Explanation: Removes the file from the staging area while keeping your actual changes intact where this is helpful when you accidentally added a file to            staging and want to revise what goes into the next commit.
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------  
