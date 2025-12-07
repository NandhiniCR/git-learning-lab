# git-learning-lab
"A clean and complete reference of essential Git commands, organized by category with clear explanations for beginners and professionals."    
NOTE:- short, professional, and strong.

Let's Start

Git commands are not infinte. They fall into 10 main categories.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
1️⃣ Setup & Configuration Commands

    A) git --version — Check installed Git version

   B) git config --global user.name "Your Name" — Set username

   C) git config --global user.email "you@example.com" — Set email

   D) git config --list — Show all config settings

   E) git help — Show Git help menu

   F) git help <command> — Explain any Git command
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
2️⃣ Repository Creation Commands

   A) git init — Create a new Git repository

   B) git clone <url> — Clone/download a remote repo

   C) git init -b main — Create repo with main as default branch

   D) git clone --branch <branch> <url> — Clone specific branch

   E) git clone --depth 1 <url> — Shallow clone (faster)

   F) git init --bare — Create a bare repository (server-style)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
3️⃣ File Tracking & Staging Commands

   A) git add <file> — Stage a file

   B) git add . — Stage all files

   C) git rm <file> — Remove file from repo & filesystem

   D) git rm --cached <file> — Stop tracking file (keep it locally)

   E) git mv <old> <new> — Rename/move a file

   F) git restore --staged <file> — Unstage file
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
4️⃣ Commit Commands

git commit -m "message" — Commit staged changes

git commit -am "message" — Add & commit tracked files

git commit --amend — Edit last commit message

git reset HEAD~1 — Undo last commit, keep changes

git reset --soft HEAD~1 — Undo commit, keep staged

git reset --hard HEAD~1 — Undo commit & delete changes
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
5️⃣ Branching Commands

git branch — List all branches

git branch <name> — Create a new branch

git branch -d <name> — Delete merged branch

git branch -D <name> — Force delete branch

git switch <name> — Switch branches

git switch -c <name> — Create + switch branch
------------------------------------------------------------------------------------------------------------------------------------------------------------------
6️⃣ Merging & Rebase Commands

git merge <branch> — Merge branch into current

git merge --abort — Cancel a conflicted merge

git rebase <branch> — Rebase on top of another branch

git rebase --continue — Continue rebase after conflict

git rebase --abort — Cancel rebase

git merge --no-ff <branch> — Create merge commit even when fast-forward
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
7️⃣ Remote Repository Commands

git remote — List remotes

git remote -v — Show remote URLs

git remote add origin <url> — Connect local repo to GitHub

git push -u origin <branch> — First push

git push — Push latest commits

git pull — Pull & merge latest updates
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
8️⃣ Undo / Reset / Clean Commands

git restore <file> — Undo file changes

git restore . — Undo all changes

git clean -n — Show what will be deleted

git clean -f — Delete untracked files

git revert <commit> — Revert a commit safely

git checkout -- <file> — Restore file to last commit
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
9️⃣ Inspection & Comparison Commands

git status — Show current status

git diff — Show unstaged file differences

git diff --staged — Show staged differences

git log — Full commit history

git log --oneline — Short history

git show <commit> — Show commit details
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔟 Advanced Commands (Real Dev Use)

git stash — Temporarily save changes

git stash pop — Restore stashed changes

git stash list — Show stashes

git cherry-pick <commit> — Apply a commit from another branch

git tag <tag-name> — Create tag

git bisect — Debug using binary search
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
