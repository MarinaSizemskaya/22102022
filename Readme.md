# `Инструкция для работы с Git и удалёнными репозиториями`
## 1. Что такое Git?
Git - это система контроля версий, которая помогает отслеживать историю изменений в файлах, имеющая как локальные, так и удалённые репозитории. Git является самой популярной реализацией систем контроля версий в мире.
## 2. Подготовка репозитория
Репозиторий – папка проекта, отслеживаемого Git, содержащая дерево изменений проекта в хронологическом порядке. Все файлы истории хранятся в специальной папке .git внутри папки проекта. Для создания репозитория необходимо выполнить команду *git init*  в папке с вашим проектом. В результате у Вас появится скрытая папка .git.
## 3. Работа с коммитами
* ### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя файла>*
* ### Создание коммитов
Коммит - это зафиксированное изменение в проекте. Для создания коммита необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>"*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
* ### Просмотр состояния репозитория
Чтобы посмотреть состояние репозитория, используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите, были измения в файлах, или нет.
* ### Журнал изменений
Чтобы посмотреть все изменения в репозитории, нужно выполнить команду *git log* в папке с репозиторием. Для выхода из журнала изменений введите *q*.
* ### Перемещение между сохранениями
Чтобы перемещаться между сохраненными изменениями, используется команда *git checkout*. Для этого в папке с репозиторием после  команды нужно ввести номер коммита: *git checkout <номер коммита>*.
## 4. Ветки в Git
* ### Создание ветки
* ### Слияние веток
* ### Удаление веток