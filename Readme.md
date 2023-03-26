# Инструкция по работе с *Git*

## Что такое *Git*
Это одна из реализаций систем контроля версий. Самая популярная версия Git - это [GitHub] (https://gitgub.com)
## Подготовка репозитория

Для создания репозитория используется команда git init. Для этого в терминале с открытой папкой с будующим репозиторием необходимо написать git init

## Создание сохранений

## Создание фиксаций

### Добавление файла к коммиту
Для того, чтобы добавить файл к будующему коммиту, используется комманда git add 
### Выполнение коммита
Для того чтобы выполнить коммит, используется команда git commit. Для этого с открытой папкой репозиторием, необходимо написать git commit -m "сообщение к коммиту". Сообщение к комиту писать оябзательно
## Переключения между фиксациями

## Журнал изменений
Для просмотра истории изменений. Используется команд git log. Для жтого в открытой папке с репозиторием нужно написать git log
## Переключения между сохранениями

## Журнал изменений
для того чтобы перейти на другой коммит, использется команда git checkout. Для этого в терминале с открытой папкой репозитория, необходимо написать git checkout <хэш(номер) коммита>. Номер коммита можно взять из журнала изменений. после этой команды вы попадете в состояние Detached head, и какие либо фиксации не будут ничего изменять. Для возврата в обычное состояние необходимо написать команду git checkout <название ветки в которой вы работали>. 
## Переключения между сохранениями



Ветки в Git
-----------

Слияние веток
------------

Удаление веток
-----------