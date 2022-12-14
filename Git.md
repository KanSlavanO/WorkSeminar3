# **_Инструкция для работы с Git и удалёнными репозиториями_**

## **Что такое Git?**
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
Подготовка репозитория
Для создание репозитория необходимо выполнить команду git init  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

---

## **Создание коммитов**

### _Git add_
Для добавления измений в коммит используется команда git add. Чтобы использовать команду git add напишите git add <имя файла>

### _Просмотр состояния репозитория_
Для того, чтобы посмотреть состояние репозитория используется команда _git status_. Для этого необходимо в папке с репозиторием написать _git status_, и Вы увидите были ли измения в файлах, или их не было.

### _Создание коммитов_
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду _git commit_. Выполняется она так: _git commit -m "<сообщение к коммиту>_. Все файлы для коммита должны быть **ДОБАВЛЕНЫ** и сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.

### _Перемещение между сохранениями_
Для того, чтобы перемещаться между коммитами, используется команда _git checkout_. Используется она в папке с репозиторием следующим образом: _git checkout <номер коммита>_

### _Журнал изменений_
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выполнить команду _git log_ в папке с репозиторием

---

## **Ветки в Git**

### _Создание ветки_

Для того, чтобы создать ветку, используется команда _git branch_. Делается это следующим образом в папке с репозиторием: _git branch <название новой ветки>_

### _Слияние веток_

Для того чтобы дабавить ветку в текущую ветку используется команда _git merge <name branch>_

---

## **Удаление веток**
Для удаления ветки ввести команду _"git branch -d 'name branch'"_
## **Добавление картинки**

![Картинка](https://i.ytimg.com/vi/T4V902rsodw/maxresdefault.jpg)
---

## **Добавление ссылки**

[Работа_С_markdown](https://lifehacker.ru/chto-takoe-markdown/?ysclid=l7nrh18u1k91907793)

---

## Работа с цитатами

>Кто глупее: дурак или тот, кто за ним следует?
>>Уберите с моей дороги этот ходячий волосатый половик!

---

## Работа со списками

Нумерованные : 

1. Первый
2. Второй
3. Третий

Ненумерованные :

* Первый
+ Второй
- Третий 

---

## __git pull__
Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

---

## __git push__
При первом её использовании нужна авторизация.
Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

---

## __Как настроить совместную работу__

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. 
    
### _GitHub при создании нового репозитория подскажет, как это можно сделать_
    
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с удаленного репозитория”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

---

## __pull request__

- _команда для предложения изменений_ 

- _запрос на вливание изменений в репозиторий_

---

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на GitHub нужно в отдельной ветке. 
Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду pull request.
    
***Как сделать pull request (по шагам)***:

- Делаем fork (ответвление) репозитория
- Делаем git clone СВОЕЙ версии репозитория
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request
