# Краткое руководство по Git
 ![А как же без картинок?](imageGIT.jpeg)
 ## Важно!
 1. git config --global user.name - Представиться программе в начале вашего знакомства 
 2. git config --global user.email - Указать email так же для знакомства 

 **Делается один раз и навсегда** 
##  Основные команды :
 * git init - создает репозиторий
 * git status - выводит информацию о состоянии репозитрия
 * git add - добавление файла для отслеживания 
 * git status - выводит информацию о состоянии репозитрия
 * git show commit_name - посмотреть полный список измениний определенного commit
 * git log -- graph - вывести измения в репозитории в виде графика 
 * git chechout commit - перейти к определнному commit для перехода необходимо указать первые 4 символа commit

 # _Просмотр изменений до коммита_

 * git diff -Можно просматривать список изменений, внесённых в репозиторий, используя параметр diff. По умолчанию отображаются только изменения, не подготовленные для фиксации.
 * git diff --staged -для просмотра подготовленных изменений необходимо добавить флаг --staged.
 * git diff file_name -Также можно указать имя файла как параметр и просмотреть изменения, внесённые только в этот файл.
 
 # Откат и удаление:
 * git revert HEAD -Создастся новый коммит, содержащий обратные преобразования относительно предыдущего, и добавится к истории текущей ветки.
 * git revert commit_name - Откатить проект до заданного коммита можно с помощью параметра revert и идентификатора коммита. Создастся новый коммит — копия коммита с предоставленным идентификатором — и добавится к истории текущей ветки.

 #  Работа с Ветками 
* git branch - выводит список веток 
* git branch branch_name - создает ветку с имеменем 
* git checkout branch_ name- переключение на ветку с именем branch_name
* git log -- graph - вывести измения в репозитории в виде графика 
* git branch -d branch_name - удаление ветки с имеменем branche_name

## 3. Работа с github
* git push - отправка репозитория на github
* git pull - Скачать удаленные данные из репозитория 
* git clone - клонировать удаленный репозиторий 