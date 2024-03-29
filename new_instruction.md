# Инструкция по работе с Git
![Логотип git](logo.png)

## Lesson 1

## Что такое git и контроль версий
**Системы контроля версий** - это системы, которые: 
1. Обеспечивают хранение содержимого файлов и папок (их *версий*).
2. Обеспечивают перемещение по *версиям* этих файлов и папок.

**Git** - это одна из самых известных и используемых на данный момент систем контроля версий с командным интерфейсом

**Локальный репозиторий** - это хранилище *изменений* Git в виде папки.

## Инициализация локального репозитория

Для того чтобы сообщить Git о том, что данная папка является локальным репозиторием и необходимо следить за изменениями в ней, находясь внутри папки следует ввести в терминале команду

**git init**

При первом использовании предварительно необлодимо представиться:

* git config --global user.name

* git config --global user.email 

## Добавление файлов

git add *имя файла*

## Сохранение изменений (версий)
git commit -m *"Комментарий к версии"*

Одновременное сохранение и добавление коммита:

git commit -am *"Комментарий к версии"*

## Просмотр текущего состояния репозитория

> git status - просмотр состояния файлов и папок в репозитории

> git diff - просмотр самих изменений файлов и папок

## Просмотр всех изменений репозитория

*git log*

## Lesson 2
## Работа с ветками
>git branch - выводит все ветки

>git branch *branch name* - создает ветки

## Lesson 3

**Новые команды**

1. cd *имя папки* - change directory, перемещение в папку;
2. git clone *путь к репозиторию* - добавление папки из **GitHub**;
3. git push - отправка текущей версии из локального репозитория в интернет;
4. git pull - загрузка версии с GitHub.

## Pull request

1. Fork из репозитория на GitHub
2. git clone собственной версии репозитория из п. 1
3. Создание ветки с предлагаемыми изменениями.
4. Сохранение необходимых изменений.
5. push в собственный репозиторий
6. Отправить pull request
