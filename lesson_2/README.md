# Lesson 2

## :computer: to install (in case you need gui)
* [GUI Clients](https://git-scm.com/downloads/guis)

## :books: to do
* [git setup](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git)
* [git alias](https://learn.javascript.ru/screencast/git#config-alias)
<!-- * []() -->


## :notebook: documentation
* [git docs](https://git-scm.com/docs)

## :pushpin: cheat sheets
* [git en](https://www.git-tower.com/blog/git-cheat-sheet/)
* [git ru](https://github.github.com/training-kit/downloads/ru/github-git-cheat-sheet/)
* [git ru](https://github.com/nicothin/web-development/tree/master/git)
* [Oh Shit, Git!?!](https://ohshitgit.com/)

```
    ls
    mkdir
    touch
    rm
    mv
    cp
    cat - показати вміст файлу
```

```
    git init
    git config --global user.name ""
    git config --global user.email ""
    git help [command]
    git add
    git commit
    git show

    git add -p - частковий add
    git commit -a -m ""
    git commit -m '' file/path

    git branch (show list of branches)
    git branch <branch> (create new branch)
    git checkout <branch>
    git checkout -b
    git checkout -f - видалити незакомічені зміни
    
    git checkout <hash> (move HEAD)
    git checkout <hash> <file> (move selected file)

    git stash
    git stash pop

    git merge <branch>
    git branch -d <brancj name> (delete branch)
    git branch -D <brancj name> (delete not merget branch)

    git reflog <branch> (show logs)
    git reset --hard @~1 (go to 1 commit back)
    git reset --soft @~1 (go to 1 commit with files)
    git reset --mixed (unstage files)
    git reset --merge (undo merge)
    git help reset  

    git commit -c, -C ORIG_HEAD (закомітити з текстом попереднього коміту)
    git commit --amend (fix last commit)

    git merge --no-ff
    git config merge.ff false
    git merge --squash

    git rebase master
    git revert <hash>
    git pull rebase

new your





```

## :octocat: advanced
* [Скринкаст по Git](https://learn.javascript.ru/screencast/git)

### Термины:

Система управления версиями — программное обеспечение для облегчения работы с изменяющейся информацией. Система управления версиями позволяет хранить несколько версий одного и того же документа, при необходимости возвращаться к более ранним версиям, определять, кто и когда сделал то или иное изменение, и многое другое.

Репозиторий — место, где хранятся и поддерживаются какие-либо данные. Чаще всего данные в репозитории хранятся в виде файлов, доступных для дальнейшего распространения по сети.


## :house: homework
1) Залить свое резюме, сделанное на первом занятии на Github и захостить на Github pages, отправить ссылку преподавателю.

   * ссылка на резюме рабочая
   * картинки отображаются

2) Залить на Github все имеющиеся практические домашние задания в разные репозитории. Добавить новую ветку в рамках репозитория с резюме и дополнить основной файл резюме ссылками на выполненные работы. Прислать преподавателю ссылку.
    * использовать хостинг с другой ветки для Github pages

## :muscle: practice
* https://githowto.com/ru 

* https://learngitbranching.js.org/ 

<!-- ## :nerd_face: in addition -->

