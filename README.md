git init

git add .
git add -A  --- Предпочтительно

git commit  --- Открывается редактор, редактор vim, cделаем VSCode

git config --global core.editor "code"

git commit  --- открывается vscode

git commit -m "Initial commit"

git branch -M master --- будущий конфликт

git remote add origin git@github.com:niihelium/git_guide_test.git

git push -u origin main  --- -u - --set-upstream  используется первый раз

git push

git branch new_feature  # Create a new branch
git checkout new_feature  # Switch to the new branch

git checkout -b new_feature  # Create and switch to a new branch

 git push -u origin new_feature

 git add -A
 git commit -m "Update new feature"

 git push

 git rebase -i HEAD~2