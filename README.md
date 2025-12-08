# git-learning-lab

Let's Start

INTRO

What is Git? 

Git is a distributed version control system that helps developers track changes in their code, work on multiple features using branches, collaborate with others, and maintain a full history of every modification.
It is the most widely used tool for managing software development projects.

Why Git Matters?

* Helps you track every change

* Makes collaboration easier

* Allows branching & merging for parallel development

* Works even without internet

* Ensures safe rollback & recoverability

About This Repository

A clean and complete reference of essential Git commands, organized by category with clear explanations for beginners and professionals."    
NOTE:- short, professional, and strong.

## Quick Navigation

Click a section to jump directly:

1️⃣ [Setup & Configuration Commands](#setup-configuration-commands)  
2️⃣ [Repository Creation Commands](#repository-creation-commands)  
3️⃣ [File Tracking & Staging Commands](#file-tracking-and-staging-commands)  
4️⃣ [Commit Commands](#commit-commands)  
5️⃣ [Branching Commands](#branching-commands)  
6️⃣ [Merging & Rebase Commands](#merging-and-rebase-commands)  
7️⃣ [Remote Repository Commands](#remote-repository-commands)  
8️⃣ [Undo / Reset / Clean Commands](#undo-reset-clean-commands)  
9️⃣ [Inspection & Comparison Commands](#inspection-comparison-commands)  
🔟 [Advanced Commands](#advanced-commands)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="setup-configuration-commands"></a>
## 1️⃣ Setup & Configuration Commands

    A) git --version — Check installed Git version

    B) git config --global user.name "Your Name" — Set username

    C) git config --global user.email "you@example.com" — Set email

    D) git config --list — Show all config settings

    E) git help — Show Git help menu

    F) git help <command> — Explain any Git command
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="repository-creation-commands"></a>
## 2️⃣ Repository Creation Commands

    A) git init — Create a new Git repository

    B) git clone <url> — Clone/download a remote repo

    C) git init -b main — Create repo with main as default branch

    D) git clone --branch <branch> <url> — Clone specific branch

    E) git clone --depth 1 <url> — Shallow clone (faster)

    F) git init --bare — Create a bare repository (server-style)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="file-tracking-and-staging-commands"></a>
## 3️⃣ File Tracking & Staging Commands

    A) git add <file> — Stage a file

    B) git add . — Stage all files

    C) git rm <file> — Remove file from repo & filesystem

    D) git rm --cached <file> — Stop tracking file (keep it locally)

    E) git mv <old> <new> — Rename/move a file

    F) git restore --staged <file> — Unstage file
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="commit-commands"></a>
## 4️⃣ Commit Commands

    A) git commit -m "message" — Commit staged changes

    B) git commit -am "message" — Add & commit tracked files

    C) git commit --amend — Edit last commit message

    D) git reset HEAD~1 — Undo last commit, keep changes

    E) git reset --soft HEAD~1 — Undo commit, keep staged

    F) git reset --hard HEAD~1 — Undo commit & delete changes
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="branching-commands"></a>
## 5️⃣ Branching Commands

    A) git branch — List all branches

    B) git branch <name> — Create a new branch

    C) git branch -d <name> — Delete merged branch

    D) git branch -D <name> — Force delete branch

    E) git switch <name> — Switch branches

    F) git switch -c <name> — Create + switch branch
------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="merging-and-rebase-commands"></a>
## 6️⃣ Merging & Rebase Commands

    A) git merge <branch> — Merge branch into current

    B) git merge --abort — Cancel a conflicted merge

    C) git rebase <branch> — Rebase on top of another branch

    D) git rebase --continue — Continue rebase after conflict

    E) git rebase --abort — Cancel rebase

    F) git merge --no-ff <branch> — Create merge commit even when fast-forward
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="remote-repository-commands"></a>
## 7️⃣ Remote Repository Commands

    A) git remote — List remotes

    B) git remote -v — Show remote URLs

    C) git remote add origin <url> — Connect local repo to GitHub

    D) git push -u origin <branch> — First push

    E) git push — Push latest commits

    F) git pull — Pull & merge latest updates
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="undo-reset-clean-commands"></a>
## 8️⃣ Undo / Reset / Clean Commands

    A) git restore <file> — Undo file changes

    B) git restore . — Undo all changes

    C) git clean -n — Show what will be deleted

    D) git clean -f — Delete untracked files

    E) git revert <commit> — Revert a commit safely

    F) git checkout -- <file> — Restore file to last commit
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="inspection-comparison-commands"></a>
## 9️⃣ Inspection & Comparison Commands

    A) git status — Show current status

    B) git diff — Show unstaged file differences

    C) git diff --staged — Show staged differences

    D) git log — Full commit history

    E) git log --oneline — Short history

    F) git show <commit> — Show commit details
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
<a name="advanced-commands"></a>
## 🔟 Advanced Commands

    A) git stash — Temporarily save changes

    B) git stash pop — Restore stashed changes

    C) git stash list — Show stashes

    D) git cherry-pick <commit> — Apply a commit from another branch

    E) git tag <tag-name> — Create tag

    F) git bisect — Debug using binary search
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
