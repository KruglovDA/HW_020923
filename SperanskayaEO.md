# **_Краткое руководство по Git_**

## Чтобы программа работала и не было ошибок, нужно предстаивться.

1. **git config** --global user.name _«Ваше имя английскими буквами»_
2. **git config --global user.email** _"адрес эл. почты"_

## **Основные команды.**

- **git init** - создает репозиторий

* **git status** - проверяем текущее состояние

## **Добавляем работу с версиями.**

- **git add** _название файла_ - добавляет файл на отслеживание
- **git commit -m** “_New file is create_”- команда сохраняет текущее состояние и текстовое напоминание.

* **git commit -a -m** “_New file is create_” - команда сохраняет все изменения в папке (~~не использовать, при создании папки, дальше можно~~)

- **git log** - смотрим предыдущие версии. ~~Когда не могу выбраться из большого перечня этих версий, можно просто нажать Q. И буду свободна!~~

- **git checkout** _цифры и буквы в 16-ричной системе счисления_ - команда открывает выбранную версию _(достаточно 4 символов)_
- **git checkout master** - команда возвращает в нормальную версию.

~~Когда надоели тонны предыдущего текста можно просто нажать **_clear_**.~~
~~Либо просто можно перезагрузить программу, либо компьютер!~~

## **Добавляем работу с ветками**

- **git branch** _name_branch_ - создать ветку с именем _name_branch_

- **git branch** - проверить какие есть ветки

* **git checkout** _name_branch_ - перейти на ветку _name_branch_
* **git checkout** -b _name_branch_ - создать и перейти на ветку _name_branch_

## Взаимодействие с GitHub.com

- **git clone** _адрес со страницы на ГитХаб_ - создает клон со страницы в ВСК.

~~Как создать репозиторий на ГитХабе со всеми командами есть на сайте GitHub.com~~

- git push - толкнуть информацию на ГитХаб
- git pull - вытянуть информацию с ГитХаба

## Надеемся данная инструкция Вам помогла, ~~если нет - Ваши проблемы~~!
