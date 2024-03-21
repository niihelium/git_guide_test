git init

git add .
git add -A  --- Предпочтительно

git commit  --- Открывается редактор, редактор vim, cделаем VSCode

git config --global core.editor "code"

git commit  --- открывается vscode

git commit -m "Initial commit"

git branch -M main

git remote add origin git@github.com:niihelium/git_guide_test.git

git push -u origin main  --- -u - --set-upstream  используется первый раз

git push

git branch new_branch_name  # Create a new branch
git checkout new_branch_name  # Switch to the new branch
