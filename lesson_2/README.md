# Lesson 2

## :computer: to install (in case you need gui)
* [GUI Clients](https://git-scm.com/downloads/guis)

## :books: to do
* [Скринкаст по Git](https://learn.javascript.ru/screencast/git)

## :notebook: documentation
* [git docs](https://git-scm.com/docs)
* [git setup](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git)
* [Командний рядок Windows. Базові команди](https://programming.in.ua/other-files/other/264-command-line-windows-basic-commands.html)

## :pushpin: cheat sheets
* [git en](https://www.git-tower.com/blog/git-cheat-sheet/)
* [git ru](https://github.github.com/training-kit/downloads/ru/github-git-cheat-sheet/)
* [git ru](https://github.com/nicothin/web-development/tree/master/git)

#### bash commands
```
    ls - відобразити вміст поточної папки
    mkdir <dir name> - створити нову папку 
    touch <file name> - створити файл
    rm <file name> - видалити файл
    mv <file name> <new file name> - перейменувати/перемістити файл
    cp <file name> <path to copy - скопіювати файл
    cat - показати вміст файлу
```

#### git main commands
```
    git init - створити новий репозиторій
    git config --global user.name "name" - встановити name користувача
    git config --global user.email "email@google.com" - встановити email користувача
    git help [command] - показати довідку

    git add . - додати всі змінені файли (до stage)
    git reset <filename> - відмінити git add для файлу <filename>
    git add -p - частковий add

    git commit -m '' - створити новий коміт
    git commit -a -m '' - додати файли до stage і створити новий коміт
    git commit -m '' <file> - створити коміт з окремим файлом <file>

    git branch - показати всі гілки
    git branch <branch> - створити гілку <branch>

    git checkout <branch> - переключитися на гілку <branch>
    git checkout -b - створити гілку <branch> і переключитися на неї
    git checkout -f - очистити незакомічені зміни
    
    git checkout <hash> - переключити репозиторій до вибраного коміту
    git checkout <hash> <file> - переключити файл до вибраного коміту
    
    git stash - покласти змінити на поличку
    git stash pop - забрати зміни з полички

    git merge <branch> - з'єднати 2 гілки в одну
    git reset --merge - відмінити merge
    git branch -d <branch name> - видалити гілку 
    git branch -D <branch name> видалити гілку (якщо воно не з'єднана з іншою)

    git reset --soft @~1 - відкатитись на 1 коміт (1 вказує на кількість комітів)
    git reset --hard @~1 - відкатитись і видалити змінені файли на 1 коміт (1 вказує на кількість комітів)

    git commit --amend - оновити попередній коміт

    git merge --no-ff - змерджити 2 гілки в одну , при цьому залишити цю гілку
    git merge --squash - змерджити 2 гілки в одну, при цьому коміти гілки яку мерджимо зклеїти в одну
    
    <!-- git config merge.ff false  -->

    git rebase master - підтягути master в гілку з переміщенням
    git revert <hash> - реверт коміта
    git pull rebase - підтянути останні зміни з origin з переміщенням

    git push origin <branch-name> - відправити локальні зміни до origin у гілку <branch-name>
    git pull origin <branch-name> - отримати origin зміни в локальний репо у гілку <branch-name>
    git fetch - підтягнути всі змінит з origin

```

## :octocat: advanced
* [Navigating the File System](https://www.codecademy.com/learn/learn-the-command-line/modules/learn-the-command-line-navigation)

### Термины:

Система управления версиями — программное обеспечение для облегчения работы с изменяющейся информацией. Система управления версиями позволяет хранить несколько версий одного и того же документа, при необходимости возвращаться к более ранним версиям, определять, кто и когда сделал то или иное изменение, и многое другое.

Репозиторий — место, где хранятся и поддерживаются какие-либо данные. Чаще всего данные в репозитории хранятся в виде файлов, доступных для дальнейшего распространения по сети.


## :house: homework
1) Залить свое резюме, сделанное на первом занятии на Github и захостить на [Github pages](https://pages.github.com/), отправить ссылку преподавателю.
   * ссылка на резюме рабочая
   * картинки отображаются

2) Залить на Github все имеющиеся практические домашние задания в репозиторий 'beetroot'.

## :muscle: practice
* https://githowto.com/ru 
* https://learngitbranching.js.org/ 

<!-- ## :nerd_face: in addition -->

