

## Что такое GitHub?
GitHub - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.


## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>* 

## Работа с удаленными репозиториями

### Основные команды
git pull позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

git push позволяет отправить локальную версию на внешний репозиторий. Требует авторизации на внешнем репозитории.

git clone загружает все изменения на локальный репозиторий и пытается слить все ветки на локальном и удаленном репозитоиях.

## Как сделать pull request

1. Делаем fork  (ответвление) репозитория 
2. Делаем git clone СВОЕЙ  версии репозитория
3. Создаем новую ветку и в НЕЕ вносим свои изменения
4. Фиксируем изменения (делаем коммиты) 
5. Отправляем свою версию в свой GitHub 
6. На сайте GitHub нажимаем кнопку pull request

## Как настроить совместную работу 
1. Создать аккаунт на GitHub.com 
2. Создать локальный репозиторий 
3. “Подружить” ваш локальный и удалённый репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории 
5. Провести изменения “с другого компьютера” 
6. Выкачать (pull) актуальное состояние из удалённого репозитория
