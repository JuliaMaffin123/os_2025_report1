---
## Front matter
title: "Внешний курс"
subtitle: "Раздел 1"
author: "Полякова Юлия Александровна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Получить базовые знания по работе с Linux с помощью внешнего курса на stepik.

# Задание

Пройти первый раздел "Введение". Выполнить тестовые и интерактивные задания.

# Выполнение этапов курса

1. Часть "Общая информация о курсе". Здесь представлены 2 ознакомительных задания.

Шаг 3 - (рис. [-@fig:001]). Название курса можно посмотреть в левом верхнем углу.

![1.1 Шаг 3](image/1.jpg){#fig:001 width=90%}

Шаг 5 - (рис. [-@fig:002]). Мной были выбраны наиболее логичные утверждения (все видны на фото), соответствующие ценностям курса.

![1.1 Шаг 5](image/2.jpg){#fig:002 width=90%}

2. Часть "Как установить Linux". Здесь 3 задания.

Шаг 6 - (рис. [-@fig:003]). Windows, так как это основная ОС на моем ноутбуке.

![1.2 Шаг 6](image/3.jpg){#fig:003 width=90%}

Шаг 8 - (рис. [-@fig:004]). Другие варианты не подходят, тем более я работаю на виртуальной машине и понимаю, что это.

![1.2 Шаг 8](image/4.jpg){#fig:004 width=90%}

Шаг 10 - (рис. [-@fig:005]). Да, удалось.

![1.2 Шаг 10](image/5.jpg){#fig:005 width=90%}

3. Часть "Осваиваем Linux". Здесь 4 задания.

Шаг 4 - (рис. [-@fig:006]). Для начала я установила через терминал LibreOffice. Затем я его открыла, создала файл и выполнила задание.

![1.3 Шаг 4, формулировка задания](image/6.jpg){#fig:006 width=90%}

Скрин файла - (рис. [-@fig:007]).

![1.3 Шаг 4, файл со строкой](image/7.jpg){#fig:007 width=90%}

Шаг 6 - (рис. [-@fig:008]). Это формат для Debian систем, конкретно Ubuntu.

![1.3 Шаг 6](image/8.jpg){#fig:008 width=90%}

Шаг 8 - (рис. [-@fig:009]). Да, удалось.

![1.3 Шаг 8, формулировка задания](image/9.jpg){#fig:009 width=90%}

Скрин запуска VLC - (рис. [-@fig:010]). Да, удалось.

![1.3 Шаг 8, запуск плеера, поиск имени автора в настройках](image/10.jpg){#fig:010 width=90%}

Шаг 10 - (рис. [-@fig:011]). Это Update менеджер, значит он для обновления.

![1.3 Шаг 10](image/11.jpg){#fig:011 width=90%}

4. Часть "Terminal: основы". Здесь 5 заданий.

Шаг 3 - (рис. [-@fig:012]). Другие варианты абсурдны.

![1.4 Шаг 3](image/12.jpg){#fig:012 width=90%}

Шаг 5 - (рис. [-@fig:013]). Регистр важен, верная команда - это pwd.

![1.4 Шаг 5](image/13.jpg){#fig:013 width=90%}

Шаг 7 - (рис. [-@fig:014]). Порядок ключей и длинная или короткая запись ключа не важны, регистр и "-" перед ключами важны.

![1.4 Шаг 7](image/14.jpg){#fig:014 width=90%}

Шаг 10 - (рис. [-@fig:015]). Мы находимся в Documents, поэтому эти две команды верны, другие из списка - нет.

![1.4 Шаг 10](image/15.jpg){#fig:015 width=90%}

Шаг 12 - (рис. [-@fig:016]). Для удаления команда rm, -r это рекурсивное удаление каталога.

![1.4 Шаг 12](image/16.jpg){#fig:016 width=90%}

5. Часть "Запуск исполняемых файлов". Здесь 3 задания.

Шаг 3 - (рис. [-@fig:017]). Проверила в своем терминале.

![1.5 Шаг 3](image/17.jpg){#fig:017 width=90%}

Шаг 6 - (рис. [-@fig:018]). & обозначает фоновый процесс, поэтому нужно bg. Ctrl + C останавливает программу, поэтому этот вариант не подходит.

![1.5 Шаг 6](image/18.jpg){#fig:018 width=90%}

Шаг 7 - (рис. [-@fig:019]). Здесь я скачала файл.

![1.5 Шаг 7, формулировка и файл для скачивания](image/19.jpg){#fig:019 width=90%}

Шаг 7 - (рис. [-@fig:020]). Я перешла в загрузки (cd), открыла доступ для исполнения (chmod +x), Затем запустила файл из текущего каталога (./). В конце я скопировала выведенный тескст и сдала в систему курса.

![1.5 Шаг 7, выполнение задания](image/20.jpg){#fig:020 width=90%}

6. Часть "Ввод / вывод". Здесь 3 задания.

Шаг 4 - (рис. [-@fig:021]). Самый логичный ответ.

![1.6 Шаг 4](image/21.jpg){#fig:021 width=90%}

Шаг 5 - (рис. [-@fig:022]). Цифра 2 означает поток ошибок, > это запись в файл, а >> это дозапись.

![1.6 Шаг 5](image/22.jpg){#fig:022 width=90%}

Шаг 7 - (рис. [-@fig:023]). Самый логичный ответ.

![1.6 Шаг 7](image/23.jpg){#fig:023 width=90%}

7. Часть "Скачивание файлов из интернета". Здесь 3 задания.

Шаг 3 - (рис. [-@fig:024]). Из-за ключей -P и -O файл сохранится именно так.

![1.7 Шаг 3](image/24.jpg){#fig:024 width=90%}

Шаг 5 - (рис. [-@fig:025]). Я посмотрела справку, а также можно догадаться логически, потому что перевод названия команды - тишина.

![1.7 Шаг 5](image/25.jpg){#fig:025 width=90%}

Шаг 7 - (рис. [-@fig:026]). Точно будут скачиваться jpg файлы, но здесь wget скачивает все файлы html, а потом удаляет ненужные.

![1.7 Шаг 7](image/26.jpg){#fig:026 width=90%}

8. Часть "Работа с архивами". Здесь 3 задания.

Шаг 3 - (рис. [-@fig:027]). Этот ответ был в материалах видео, которое я ранее смотрела в предыдущем шаге.

![1.8 Шаг 3](image/27.jpg){#fig:027 width=90%}

Шаг 5 - (рис. [-@fig:028]). tar - архиватор, значит да. gzip - это компрессор, он еще больше сжимает архив, поэтому нет. А zip - и архиватор, и компрессор, значит да.

![1.8 Шаг 5](image/28.jpg){#fig:028 width=90%}

Шаг 7 - (рис. [-@fig:029]). Во-первых нужно c, чтобы создать архив и j, чтобы был формат bz2, поэтому остальное неверно.

![1.8 Шаг 7](image/29.jpg){#fig:029 width=90%}

9. Часть "Поиск файлов и слов в файлах". Здесь 3 задания.

Шаг 3 - (рис. [-@fig:030]). Вариант \*.jpg - не соответствует расширение; \*.? - здесь ? это 1 символ, а после точки их 4; alexey.* - первая буква не того регистра.

![1.9 Шаг 3](image/30.jpg){#fig:030 width=90%}

Шаг 5 - (рис. [-@fig:031]). Регистр важен, соседние символы не важны, важно четкое совпадение сочетания букв.

![1.9 Шаг 5](image/31.jpg){#fig:031 width=90%}

Шаг 6 - (рис. [-@fig:032]). Здесь я скачала архив.

![1.9 Шаг 6, формулировка и ссылка на архив](image/32.jpg){#fig:032 width=90%}

Шаг 6 - (рис. [-@fig:033]). Распаковываем скачанный архив, результат команды grep поиска шаблона рекурсивно в распакованной ранее папке отправляем в результирующий файл.

![1.9 Шаг 6, выполнение задания](image/33.jpg){#fig:033 width=90%}

# Выводы

Был полностью завершен первый раздел внешнего курса.
