# repo-local-first
# test_repo_2_2
Test repo for Classroom task 2.2

Commands that I used for this repo:

___

```bash

git init
git add .
git commit -m "Initial commit"
git remote add origin git@github.com:olexxxxx/local_repo_2_2.git
echo "# repo-local-first" > README.md
 cat > .gitignore << 'EOF'

##### VisualStudioCode ###
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
!.vscode/*.code-snippets

# Local History for Visual Studio Code
.history/

# Built Visual Studio Code Extensions
*.vsix

### VisualStudioCode Patch ###
# Ignore all local history of files
.history
.ionide

### Windows ###
# Windows thumbnail cache files
Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file
*.stackdump

EOF
git remote set-url origin git@github.com:olexxxxx/test_repo_2_2.git
git push origin main

___
