# Project_Dev
A group project that trains collaboration and simulates teamwork.


## How to clone project

### Install Git 
- Download Git for Windows: https://git-scm.com/install/windows
- Download Git for Mac: https://git-scm.com/install/mac 

### Copy this Url (Project URL)
- [Clone using the web URL](https://github.com/BetterCallYee/Dev_Group_Project.git)
- https://github.com/BetterCallYee/Dev_Group_Project.git

### Open VScode
- (Ctrl + Shift + P)
- Git: Clone
- (Ctrl + V) or https://github.com/BetterCallYee/Dev_Group_Project.git
- Select folder


### Create your own branch (very important)
- Open Vscode Terminal 
### Create Your Branch
- git checkout -b branch_Name

Example: git checkout -b feature-login

### check your branch
- git status 


### when you finish your code
- git add. 
- git commit -m "commit_Name"

Example: git commit -m "Login"
- git push origin branch_Name

Example: git push origin feature-login


### Update project to match the main repository.
This should be done every time before starting work.
- git checkout main
- git pull origin main
