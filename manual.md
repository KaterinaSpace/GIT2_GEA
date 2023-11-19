Инструкция по Markdown 
Создала Гольцева Екатерина

Списки

* one
* two
* three
* four
  * four 1
  * four 2
    * four 2 1
    * four 2 2

1. one
1. two
1. three
1. four
   1. four 1
   1. four 2
      1. four 2 1
      1. four 2 2

Форматирование текста 

**жирный**

*курсив*

~~зачеркнутый~~

__жирный__

_курсив_

Добавление картинки 
![скрин](3.jpg)
![скрин](2.jpg)

## Установка Git

* Windows. Проходим по [этой ссылке](https://git-scm.com/download/win "Download for Windows"), выбираем под вашу ОС (32 или 64 битную), скачиваем и устанавливаем.

* Для Mac OS. Открываем терминал и пишем:

Если установлен Homebrew

>brew install git

Если нет, то вводим эту команду. 

> git --version

После этого появится окно, где предложит установить Command Line Tools (CLT).

Соглашаемся и ждем установки. Вместе с CLT установиться и git

* Linux. Открываем терминал и вводим следующую команду.

 Debian или Ubuntu

> sudo apt install git

 CentOS

> sudo yum install git
