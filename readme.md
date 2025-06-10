Git Configuration
git --version
git config --global user.name "krishnendu dalui"

git config --global user.email "krishnendudalui@gmail.com"
git config --global user.email
git config --global user.name


🛠️ Initialize Git Repository
git init


🚀 First Commit


ls -a
git add main.py
git status
git commit -m"initial commit"




📝 Make Changes and Commit

git status
git add .
git status
git commit -m"nav bar create"
git status
git log




✨ Another Change and Commit
git add .
git status
git commit -m "h-font added in navbar"
git status
git log




🧹 Clean Terminal
clear


📂 Add Specific File
git add "index.php"
git commit -m "index.php added"
git log




⏪ Checkout to Specific Commit
git log 
git checkout a0aa7039e19b925a75bac681444d0b4bf902ed0d
git log









🌿 Branch Management
git branch
git log 
git checkout master
git log 



🚀 Branch create 
git branch dev
git branch
git checkout dev
git branch
git checkout -b "krshnendu/login"
(name & feature)
git branch




📂 Add Specific File
git add "index.html"
git status
git commit -m "index.html added"
git status
git log




🌿 switching branch 
git branch
git checkout dev
git log 



🛑 How to Exit Git Log View:
👉 Press the Q key (q for quit)


🔀 Git Merge: 
git checkout dev
git merge krshnendu/login

git branch
git checkout master
git merge dev 


🙈 .gitignore in Git: 

Git branch
Git checkout krshnendu/login
touch .gitignore

Git add .
Git commit -m “ gitignore”
Git status 


# Ignore Python cache
__pycache__/

# Ignore compiled files
*.pyc

# Ignore environment files
.env

# Ignore node_modules (for JS projects)
node_modules/

# Ignore log files
*.log

# Ignore system files
.DS_Store
Thumbs.db





🟦 Step 1: Log in to GitHub
🟦 Step 1: Log in to GitHub
Go to https://github.com


Log in to your account



🟦 Step 2: Create a New Repository
Click the + icon (top-right corner)


Select "New repository"



📝 Step 3: Fill in Repository Details
Field
Description
Repository name
e.g., ai_project
Description (optional)
e.g., "My AI video app using Pipenv and Python"
Visibility
Public or Private
Initialize with README
Optional – only check this if you are not pushing local files yet

Then click "Create repository"



## push an existing repository from the command line
git remote add origin git@github.com:Code-with-nandu/github.git
git remote -v
git branch -M master
git push -u origin master

📤 15. Push First Time (After init)