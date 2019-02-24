# Git basic commands
Some frequently used Git basic commands are listed below:


| Command | Definition |
| ------- | ---------- |
|`git status` | Show the working tree status |
| `ls` | Show information about files in the index and the working tree |
| `pwd` | Print current working directory |
| `mkdir <folder name>` | Creating new working directory with new "folder name" |
| `cd <folder name>` | Changing directory to "folder name" |
| `git init demo` |  Create an empty Git repository "demo" |
| `Notepad++ README.md` | Open text editor to modify README.md file |
| `git add README.md` | Add "README.md" file to staging area |
| `git commit -m"Adding README.md"` | Commit all files in staging area with message"Adding README.md" |
| `git commit -am"Updating README.md"` | A more convenient way to automatically stage all tracked, modified files and commit them |
| `cd ..` | Change current directory to parent directory |
| `git add .` | Add all untracked files to staging area |
| `git reset HEAD README.md` | reset back to the previous status |
| `git checkout -- README.md` | restore working tree files "README.md" |
| `git mv example.txt demo.txt` | move example.txt to new name demo.txt |
| `git rm demo.txt` | remove demo.txt |
| `git checkout -b updates` | Create a new branch "updates" and switch to this new branch |
| `git merge updates` | merge branch "updates" into master branch |
| `git branch -d updates` | delete the branch "updates" |
| `git branch -a` | Check all the branches |
| `git checkout master` | Return to master branch |
