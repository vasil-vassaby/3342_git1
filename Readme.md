# Инструкция для работы с Git и удалёнными репозиториями 
___

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git).
## Установка и настройка
Для Windows проходим по [этой ссылке](https://git-scm.com/download/win/), выбираем Git под вашу ОС (32 или 64 битную), скачиваем и устанавливаем.
## Создание коммитов

### Git add
Для добавления файлов в репозиторий используется команда *git add*. Чтобы добавить конкретный файл напишите *git add <имя файла>*.

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>"*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*.

## Журнал изменений
Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.
## Процесс работы с Git
Не стоит после каждого изменения файла делать commit. Чаще всего их создают, когда:
* *Создан новый функционал*
* *Добавлен новый блок на верстке*
* *Исправлены ошибки по коду*
* *Вы завершили рабочий день и хотите сохранить код*

Это поможет держать вашу ветку в чистоте и порядке.
## Ветки в Git
![простая ветка](ветка.jpg)

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*.

### Слияние веток

Для того, чтобы дабавить ветку, в текущую ветку используется команда *git merge <название ветки>*.

### Удаление веток
Для удаления ветки ввести команду *git branch -d <название ветки>.*

### Перемещение между ветками
Переключаться между ветками можно командой: *git checkout <название ветки>*.
## GitHub что это?
GitHub — это веб-служба размещения для репозиториев Git. В GitHub размещается основной репозиторий всех проектов. Из этого репозитория участники копируют свою работу.
## Настройка удаленного репозитория
Перед началом нужно зарегистрироваться на [GitHub](https://github.com/).  

Далее переходим на среду разработки Visual Studio Code (VS Code).
В VS Code находим и нажимаем на область Система управления версиями.
После нажатия на кнопку *__Publish to GitHub__*, появится всплывающее окно. Нужно выбрать второй вариант или там где присутствует фраза *...public repository*.

Вы создали и опубликовали репозиторий на GitHub.
___

