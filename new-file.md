# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире. Cейчас мы его изучаем.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'" тема следующей лекции!!!000 
Этот комент должен будет приходить из ветки которую я удалю пользуясь командй выше!!!

# создание картинок

не могу понять почему при переходе по веткам остаются предыдущие действия!!

для создания картинок используются следующие действия:
! - просто он нужен [] - коммент на случай если картнка исчезнет () - тут сылка на картинку!!!
![100% кошка](./CAt.webp)

# Создание цитат
для создания цитат мы используем знак больше ">"
возможно делать цитаты в цитатах для этого мы добавляем еще знак >

>Так может выгледеть 
>>цитата
>>>!!!

### отступление
эта ветка лыла создана так же как и все предыдкщие для выполнения дз!
а еще из за того что я забыл называть(коментить) ветки которые я сливаю

# pull push clone

Команда pull переводится как тянуть, она стягивает данные с сервера на компьютер (переносит от кудота на нас)

Команда push переводится как толкать, она передает информацию с нашего компьютера на сервер

Команда clone копирует исходный код с ервера нам на компьютер создовая все что было на сервере у нас на компьютере


# godbay

## end

![theEnd](./EnD.jpg)