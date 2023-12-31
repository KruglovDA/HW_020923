# Краткое руководство по  Git

## 1. Основные команды

* git init - создает репозиторий
* git status - выводит информацию о состоянии репозитория
* git log - отображает лог коммитов и слияний
* git log --graph - добавляет график правок и слияний
* git add <filename> - добавить файл в индекс Git
* git commit -am "text" - создать коммит, т.е. передает изменения из индекса в репозиторий
* git commit --amend -m "text" - изменить комментарий активного коммита
* git checkout <hash> - переключение на другой коммит
* git reset HEAD~ - удаление последнего коммита из репозитория
* git reset --hard HEAD~ - удаление последнего коммита и откат изменений

## 2. Работа с ветками

* git branch - выводит список веток репозитория
* git branch <branch_name> - создать новую ветвь с именем branch_name
* git checkout <branch_name> - переключение на другую ветвь
* git checkout -b <branch_name> - переключиться на вновь созданную ветвь <branch_name>
* git branch -m <name> <new_name> - переименовать ветку <name> в <new_name>
* git branch -m <new_name> - переименовать текущую активную ветку в <new_name>

## 3. Работа с Github
* git clone <url> - создать локальную копию репозитория по адресу <url>. Склонированный репозиторий будет автоматически связан с удаленным.
* git remote add <name> <url> - связать локальный репозиторий с удаленным репозиторием по адресу <url>. Используется общепринятое стандартное обозначение удаленного репозитория origin (<name> = origin). <name> может быть и другой.
* git push -u origin main - оправить изменения в локальной ветке main в удаленный репозиторий origin. Последующие "пуши" можно делать так:
* git push

* git push <remote name, e.g. origin> <local branch name>:<remote branch name> - можно запушить ветку из одного локального репозитория в другой с переименованием, например:
git push ../Seminar_2023-09-09_homework main:ShefA
Запушатся все коммиты из исходного репозитория, но в репозитории назначения ветку ShefA нельзя будет слить с main из-за разных родителей.

* git pull - загрузить изменения из удаленного репозитория в локальный
