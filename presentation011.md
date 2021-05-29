# презентация по лабораторной работе №11

----

# Тема:
## Программирование в командном процессоре ОС UNIX. Командные файлы

----

## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Бен бадр Ясмин

Группа: НКНбд-01-20

Москва, 2021г.

----

#Введение 
###GZIP

Утилита gzip уменьшает размер указанных файлов за счет кодирования по алгоритму Лемпела-Зива (Lempel-Ziv coding - LZ77). По возможности каждый файл заменяется одноименным файлом с расширением .gz, с сохранением тех же прав доступа, владельца и времени изменения. 

Утилита gzip будет пытаться сжимать только обычные файлы. В частности, она будет игнорировать символические связи.


### Ход работы:

1. сначала я вошла в gzip, Изучила опции команды, с помощью команды man.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/Screenshot%202021-05-29%20011315.png)

* используя команду touch я Создала текстовой файл lab11_1.sh,. Открывала текстовой редактор emacs.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/2.png)


* Написала код, в котором я создаю папку backup, копировала текстовой файл lab11_1.sн, указав путь для сохранения файла. После архивировала данный файл через команду gzip.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/3.png)

* написала Командой chomad чтобы файл был исполняемым в Linux.
  ![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/4.png)
*  Провеила, сесли  можно выполнить  программу. Папка backup была создана.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/5.png)

* Проверила, возможность выполнить мою программу.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/6.png)


1. Создала новый файл lab11_2.sh, используя команду touch. Открываю текстовой редактор emacs.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/7.png)

* Написала программу, для вывода того, что я буду вводить.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/8.png)

*использовала Командой chomad, чтобы файл был исполняемым в Linux. Следующая строка для того, чтобы он выполнила  ранее написанную программу.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/9.png)


1. Создала текстовой файл lab11_3.sh, используя команду touch. Открываю текстовой редактор emacs.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/10.png)

*  Написала командный файл — аналог команды ls .

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/11.png)

*  выдавление информацию о нужном каталоге и выводил информацию о возможностях доступа к файлам этого каталога.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/12.1.png)
![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/12.png)

1. Создала текстовой файл lab11_4.sh, используя команду touch. Открываю текстовой редактор emacs.

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/13.png)

* Написала командный файл, который получает в качестве аргумента командной строки формат файла (.txt, .doc, .jpg,  pdf и т.д.).

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/14.png)

*  Вычисляет количество таких файлов в указанной директории. Путь к директории также передаётся в виде аргумента командной строки. 

![](https://raw.githubusercontent.com/benbaderyasmine/lab11/main/photo/lab11/15.png)

----

### Вывод

Изучила основы программирования в оболочке ОС UNIX/Linux, научилась писать небольшие командные файлы.

----

### Библиография

[Командные файлы Linux](https://sgww.livejournal.com/8836.html)
[Командные процессоры (оболочки)](https://infopedia.su/24x10498.html)

----

