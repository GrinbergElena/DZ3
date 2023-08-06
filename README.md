# Инструкция для работы с Cit и удаленными репозиториями

Что такое Git?
---
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)
# Создание коммитов
## Git add
Для добавления измений в коммит используется команда _git add._ Чтобы использовать команду _git add_ напишите _git add <имя файла>_
## Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда _git status_. Для этого необходимо в папке с репозиторием написать _git status_, и Вы увидите были ли измения в файлах, или их не было.
## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду _git commit_. Выполняется она так: _git commit -m "<сообщение к коммиту>_. Все файлы для коммита должны быть **ДОБАВЛЕНЫ** и сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.
# Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда _git checkout_. Используется она в папке с репозиторием следующим образом: _git checkout <номер коммита>_
# Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выполнить команду _git log_ в папке с репозиторием
# Ветки в Git
## Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*
## Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*
## Удаление веток
Для удаления ветки ввести команду *"git branch -d 'name branch'"*

# Работа с удаленными депозиториями
## Синхронизация
Входим в GitHub через барузер по умолчанию. В ВизуалСтудиоКод  синхронизируем параметры.Проверяем.
## Новый репозиторий
в GitHub создаем новый репозиторий и копируем ссылку
в VSC открываем нужную папку и в командной строке терминала вставляем три скопированные строки из GitHub
Наша ветка On branch main, Your branch is up to date with 'origin/main'
## Размещение файла в репозитории
команда git push отправляет файл из VSC в GitHub
## Редактирование
Редактировать можно как в VSC так и в  GitHub. Изменения сохраняются добавлением коммитов. Изменения из GitHub  в VSC исполняются командой git pull
## Редактирование файла из чужого репозитория
1. По предоставленной ссылке или поиску заходим в репозиторий другого пользователя в GitHub
2. Кнопка Fork. Подтверждаем Create fork
3. В своем репозитории, в скопированной папке, кнопка Code. Copy.
4. В VSC вставляем в коммандную стороку  git clone скопированная_ссылка В проводике появится нужная папка
5. встаем на папку и открываем в новом встроенном терминале.
6. В главной ветке работать с запуленными файлами нельзя, поэтом создаем новую ветку git chekhout name_branch
7. Открываем нужный файл. Редактируем. Комментим.
8. Отправляем изменения в GitHub коммандой git push
9. В GitHub  в своем репозитории делаем pull reguests папки другого пользователя.
author: GrinbergElena <sub>Magadan</sub>