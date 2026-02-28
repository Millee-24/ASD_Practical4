# ASD_Practical5
Git Demo
This is a demo repository created to practice Git and Git Hub operatiosn like pushing, pulling, cloning and committing changes.
It is used for learning version control and repository management.
Objective:
Learning to manage project files using git hub. 
To understand the basic git commands.
Tools used:
Git Hub 
Git Bash
Visual Studio Code
Git Commands Practiced:
Commands on GitBash - >
git --version
ls
pwd
git conifg --global user.name "Enter your github's user name"
git config --global user.email "Enter the emial which is currently working on github"
git config --list
commands on VS Code ->
git --version
pwd
mkdir GitDemoProject
cd GitDemoProject
git clone "https:/(Enter the https link here)"
cd ASD_Practical4 (Enter the name of your repository here)
ls
code . (This will open the repository folder in git hub)
# Did the changes in readme file on VS code
git status
git add README.md
git commit -m "Updated the README.md file" 
#Changes get stored in local repository, it get stored permanently on your system but not yet visible online to make the changes visible online follow the next command
git push


