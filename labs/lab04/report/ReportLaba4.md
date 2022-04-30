# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ  
Факультет физико-математических и естественных наук  
Кафедра прикладной информатики и теории вероятностей

Отчет по лабораторной работе №4:  
"Лабораторная работа № 4. Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки" 

Дисциплина: Операционные системы  
Автор: Шмырин Михаил Сергеевич  
Номер группы: НПМбд-02-21  
Преподаватель: Кулябов Дмитрий Сергеевич

Москва

2022г.

# 4.1. Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# 4.2. Указания к работе

В операционной системе типа Linux взаимодействие пользователя с системой обычно
осуществляется с помощью командной строки посредством построчного ввода команд. При этом обычно используется командные интерпретаторы языка shell: /bin/sh;
/bin/csh; /bin/ksh

# 4.3. Последовательность выполнения работы
## 	1.	Определяем полное имя домашнего каталога с помощью команды pwd (рис. 1)

![Рис 1.](image/Picture1.jpg)

## 2.	Выполним действия:
### 1)	Переходим в каталог /tmp. Выводим на экран содержимое каталога/tmp.Для этого используем команду ls с различными опциями.
“ls” - выводится список каталогов и файлов, которые можно увидеть, “вручную” открыв каталог tmp (рис. 2)
![Рис 2.](image/Picture2.jpg)

# “ls -a” - к списку, описанному в предыдущем пункте, добавляются скрытые каталоги и файлы (рис. 3)
![Рис 3.](image/Picture3.jpg)

## “ls -F” - с помощью этой команды получаем информацию о типах файлов (рис. 4)
![Рис 4.](image/Picture4.jpg)

# “ls -l” - получаем список каталогов и файлов, но уже с более подробной информацией о них (рис. 5)
![Рис 5.](image/Picture5.jpg)

## “ls -alF” - данная команда отображает список всех каталогов и файлов, в том числе и скрытых, с подробной информацией о них (рис. 6)
![Рис 6.](image/Picture6.jpg)

# 2)	Определяем ,есть ли в каталоге /var/spool подкаталог с именем cron (рис. 7)
![Рис 7.](image/Picture7.jpg)

## 3)	Переходим в домашний каталог и выводим на экран его содержимое (рис. 8)
![Рис 8.](image/Picture8.jpg)

# 3.	Выполним действия:
## 1)	В домашнем каталоге создаем новый каталог с именем newdir. В каталоге ~/newdir создаем новый каталог с именем morefun (рис. 9)
![Рис 9.](image/Picture9.jpg)

### 2)	В домашнем каталоге создаем одной командой три новых каталога с именами letters, memos, misk. Затем удаляем эти каталоги одной командой.(рис. 10)
![Рис 10.](image/Picture10.jpg)

# 3)	Попробуем удалить ранее созданный каталог ~/newdir командой rm. Он не удалён.(рис. 11)
![Рис 11.](image/Picture11.jpg)
## 4)	Удаляем каталог ~/newdir/morefun из домашнего каталога. Проверяем, был ли каталог удалён. (рис. 12)
![Рис 12.](image/Picture12.jpg)

# 4.	С помощью команды man определяем, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него.(рис. 13)
![Рис 13.](image/Picture13.png)

## 5.	С помощью команды man определите опцию команды ls, позволяющую отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.(рис. 14)
![Рис 14.](image/Picture14.png)

# 6.	Используем команду man для просмотра описания следующих команд:cd,pwd,mkdir,rmdir,rm.
## 1)	Описание команды сd (рис. 15)
![Рис 15.](image/Picture15.png)

# 2)	Описание команды pwd (рис. 16)
![Рис 16.](image/Picture16.png)

# 3)	Описание команды mkdir (рис. 17)
![Рис 17.](image/Picture17.png)

# 4)	Описание команды rmdir (рис. 18)
![Рис 18.](image/Picture18.png)

# 5)	Описание команды rm (рис. 19)
![Рис 19.](image/Picture19.png)



