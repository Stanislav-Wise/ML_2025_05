Установка git
https://git-scm.com/
https://www.toptal.com/developers/gitignore

sudo apt install git

brew install git


git --version


Настройка

git config --global user.name "Ваше имя"
git config --global user.email "mail@email.com"

git config --list

git config --global init.defaultbranch main


Работа с git

git status

git add .gitignore

git commit -m "Initial commit"

git rm --cached <файл> -   убрать из индекса


git log

git add ./

