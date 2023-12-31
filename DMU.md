![plot](./DMU_GitLogo.png)
## Работа с Git
### Что такое Git?
Git - система контроля версии проекта, предназначена для хранения всех изменений и свободного доступа к любой из них.

### Ссылка на скачивание 
Скачать Git можно по [ссылке](https://git-scm.com/downloads)

### Ветвление
![plot](./DMU_Branches.png)
Также он является удобным инструментом для командной работы, в котором каждый работает над своей конкретной задачей. По их выполнении изменения объединяются.

### Команды Git
Для осуществления контроля версиями через терминал используются следующие команды:

**внимание: перед всеми командами нужно писать: <ins>git</ins>**

| команда      | назначение |
|--------------|------------|
| init | Создание репозитория (самая первая команда для нового проекта)
| add [file]   | добавление в гит файла (начинать отслеживать его изменения) |
| commit -m    | создание комита (сохранение новых изменений в гит) (-m дополнительный параметр, отвечающий за название комита)
| status | проверка отлеживаемых файлов на наличие изменений
| log | отображение всей комитов репозитория
| checkout [id]| перемещение id-версию (с одного комита на другой) (id каждого измениния можно посмотреть в log) (если вместо id поставить '-', то проихойдет перемещение к последней версии)
|branch | отображение всех веток репозитория
|branch [name]|Создание ветки (с определенным имененм)
|checkout [name]|Переключение на ветку [name]
|merge [name]|Добавление в текущую ветку все изменения ветки [name]
|cherry-pick [id]|перенести коммит с [id] с одной ветки на текущую. Коммит будет считаться для данной ветки новым, а не наследуемым как в merge|

## Команды GitHub
Эти команды поддерживает не сам git, а сервис GitHub, который предоставляет удаленные (облачные) сервера для хранения репозиториев (называются удаленными)

| команда      | назначение |
|--------------|------------|
|clone [link]|копирование удаленного репозитория|
|pull|забрать последние изменения текущей ветки с удаленного репозитория, по их скачиванию выполняется merge
|push|отправить на удаленный репозиторий новые изменения на текущей ветке 
|pull request| запрос на изменение в удаленный репозиторий (что-то похожее на коммит, только может состоять из нескольких коммитов и можно написать подробное описание)