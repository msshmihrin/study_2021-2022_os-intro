---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №7
author: |
	Шмырин Михаил Сергеевич (группа: НПМбд-02-21)
institute: |
	Российский Университет Дружбы Народов

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель работы
Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

# Задание по mc

1. Изучил информацию о mc, вызвав в командной строке man mc. Узнал, что MC - это псевдографическая командная оболочка для систем.(рис. [-@fig:001])

![Информация о mc](image/2.1.jpg){ #fig:001 width=70% }

## Структура и меню mc

2. Запустил из командной строки mc, изучил его структуру и меню. В стандартном состоянии окно редактора состоит из двух панелей. Верхнее меню содержит меню "Левая панель" (рис. [-@fig:002]), "Файл" (рис. [-@fig:003]), "Команда" (рис. [-@fig:004]), "Настройки" (рис. [-@fig:005]), "Правая панель" (рис. [-@fig:006]).

![Левая панель](image/2.2.jpg){ #fig:002 width=70% }

## Файл

![Файл](image/2.3.jpg){ #fig:003 width=70% }

## Команда

![Команда](image/2.4.jpg){ #fig:004 width=70% }

## Настройки

![Настройки](image/2.5.jpg){ #fig:005 width=70% }

## Правая панель

![Правая панель](image/2.6.jpg){ #fig:006 width=70% }

## Выполнение операций в mc

3. Выполнил несколько операций в mc, используя управляющие клавиши.

  1) Выделение файлов (клавиша insert) (рис. [-@fig:007])

![Выделение файлов](image/2.7.jpg){ #fig:007 width=70% }

## Выделение/отмена выделения файлов

  2) Для выделения файлов или его отмены можно использовать команды "Снять отметку", "Обратить выделение" в меню "Файл" (рис. [-@fig:008])

![Выделение/отмена выделения файлов](image/2.8.jpg){ #fig:008 width=70% }

## Копирование и перемещение файлов

  3) Для копирования файлов используется клавиша F5 (рис. [-@fig:009]), клавиша F6 используется для перемещения (рис. [-@fig:010])
  
![Копирование файлов](image/2.9.jpg){ #fig:009 width=70% }

![Перемещение файлов](image/2.10.jpg){ #fig:010 width=70% }

## Информация

  4) Для получения информации можно перейти в "Левая панель" -> "Информация" (рис. [-@fig:011])
  
![Информация](image/2.11.jpg){ #fig:011 width=70% }

## Формат списка

  5) "Левая панель" -> "Формат списка" -> "Расширенный" (рис. [-@fig:012]) (рис. [-@fig:013])
  
![Формат списка](image/2.12.jpg){ #fig:012 width=70% }
  
![Изменение формата списка](image/2.13.jpg){ #fig:013 width=70% }

## Права доступа

  6) "Файл" -> "Права доступа" (рис. [-@fig:014])
  
![Права доступа](image/2.14.jpg){ #fig:014 width=70% }

## Расширенные права

  7) "Файл" -> "Права"(расширенные). Помимо названия файл или каталога выводит сведения о правах
доступа, владельце, группе, размере, времени правки (рис. [-@fig:015])
  
![Расширенные права](image/2.15.jpg){ #fig:015 width=70% }

## Выполняю основные команды меню правой панели.

4. Выполняю основные команды меню правой панели.

  1) "Список файлов" отображает размер файл и время его правки (рис. [-@fig:016])
  
![Список файлов](image/2.16.jpg){ #fig:016 width=70% }

## Быстрый просмотр

  2) "Быстрый просмотр" нужен для предпросмотра содержания файла.(рис. [-@fig:017])
  
![Быстрый просмотр](image/2.17.jpg){ #fig:017 width=70% }

## Информация
  
  3) "Информация" отображает подробные данные о файле (рис. [-@fig:018])
  
![Информация](image/2.18.jpg){ #fig:018 width=70% }

## Дерево
  
  4) "Дерево" необходим для просмотра дерева каталога (рис. [-@fig:019])
  
![Дерево](image/2.19.jpg){ #fig:019 width=70% }

## Выбор кодировки

  5) "Выбор кодировки" нужен для просмотра и смены кодировки (рис. [-@fig:020])
  
![Выбор кодировки](image/2.20.jpg){ #fig:020 width=70% }

## 5. Используя возможности подменю "Файл", выполняю:

  1) просмотр и редактирование содержимого текстового файл (рис. [-@fig:021])
  
![Просмотр содержимого текстового файла](image/2.21.jpg){ #fig:021 width=70% }

## Создание каталога

  2) создание каталога (рис. [-@fig:022])
  
![Создание каталога](image/2.22.jpg){ #fig:022 width=70% }

## Копирование

 3) копирование в файлов в созданный каталог(рис. [-@fig:023])
  
![Копирование](image/2.23.jpg){ #fig:023 width=70% }

## 6. С помощью соответствующих средств подменю "Команда" осуществил:

  1) Поиск в файловой системе файл с заданными условиями (например, файла
с расширением .cрр) (рис. [-@fig:024])
  
![Поиск](image/2.24.jpg){ #fig:024 width=70% }

  2) Выбор и повторение одной из предыдущих команд. Перешл в пункт "История" командной строки и увидел, что появилась строка История, но она пустая, потому что командная строка не был использована.
  
## Переход в домашний каталог

  3) Перешел в домашний каталог с помощью Дерева каталогов (рис. [-@fig:025])
  
![Переход в домашний каталог](image/2.25.jpg){ #fig:025 width=70% }

## Операции, определяющие структуру экрана mc
  
7. Вызвал подменю "Настройки". Освоил операции, определяющие структуру экрана mc.

  1) Конфигурация — позволяет скорректировать настройки работы с панелями.(рис. [-@fig:026])
  
![Конфигурация](image/2.26.jpg){ #fig:026 width=70% }

## Внешний вид и настройка панелей
  
  2) Внешний вид (рис. [-@fig:027]) и Настройки панелей (рис. [-@fig:028]) — определяет элементы (строка меню, командная строка, подсказки и прочее), отображаемые при вызове mc, а также геометрию расположения панелей и цветовыделение.
  
![Внешний вид](image/2.27.jpg){ #fig:027 width=70% }

## Настройка панелей

![Настройки панелей](image/2.28.jpg){ #fig:028 width=70% }

## Биты символов

  3) Биты символов — задаёт формат обработки информации локальным терминалом.(рис. [-@fig:031])
  
![Биты символов](image/2.31.jpg){ #fig:031 width=70% }

## Подтверждение

  4) Подтверждение — позволяет установить или убрать вывод окна с запросом подтверждения действий при операциях удаления и перезаписи файлов, а также при выходе из программы (рис. [-@fig:029])
  
![Подтверждение](image/2.29.jpg){ #fig:029 width=70% }

## Оформление

  5) Оформление - позволяет менять цветовую гамму визуальной оболочки (рис. [-@fig:030])
  
![Оформление](image/2.30.jpg){ #fig:030 width=70% }

# Задание по встроенному редактору mc

## Создание текстового файл text.txt


1. Создаю текстовой файл text.txt. (рис. [-@fig:032])
  
![Создание текстового файл text.txt](image/2.32.jpg){ #fig:032 width=70% }

## 2. Открыл этот файл с помощью встроенного в mc редактора.

3. Вставил в открытый файл небольшой фрагмент текста, скопированный из Интернета.(рис. [-@fig:033])
  
![Вставил фрагмент текста из Интернета](image/2.33.jpg){ #fig:033 width=70% }

## 4. Проделайте с текстом следующие манипуляции, используя горячие клавиши:

  1) Удалил строку текста с помощью клавиши F8.
  
  2) Выделил фрагмент текста (F3) и скопировал его на новую строку (F6).
  
  3) Сохранил файл с помощью клавиши F2.
  
  4) Отменил последнее действие с помощью комбинации ctrl+u.
  
  5) Перешел в конец файл (ctrl+end) и написал строку "Лабораторна работа №7". Перешел в начало файл (ctrl+home) и написал строку "4 мая 2022 год" (рис. [-@fig:034])
  
![Изменение](image/2.34.jpg){ #fig:034 width=60% }
  
  7) Сохранил файл (F2) и вышл из него.
  
6. Используя меню редактора, выключил подсветку синтаксиса.

# Выводы

Я освоил основные возможности командной оболочки Midnight Commander. Приобрел навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.
