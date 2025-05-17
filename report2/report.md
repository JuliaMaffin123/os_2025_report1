---
## Front matter
title: "Внешний курс"
subtitle: "Раздел 2"
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

Пройти второй раздел "Работа на сервере". Выполнить тестовые и интерактивные задания.

# Выполнение этапов курса

1. Часть "Знакомство с сервером". Здесь представлены 2 задания.

Шаг 3 - (рис. [-@fig:001]). Все варианты логичные, и они упоминались в видео.

![2.1 Шаг 3](image/1.jpg){#fig:001 width=90%}

Шаг 6 - (рис. [-@fig:002]). pub - это public, то есть его можно безопасно пересылать.

![2.1 Шаг 6](image/2.jpg){#fig:002 width=90%}

2. Часть "Обмен файлами". Здесь 3 задания.

Шаг 4 - (рис. [-@fig:003]). Здесь нужно -r, чтобы скопировать со всеми подпапками, поэтому этот вариант.

![2.2 Шаг 4](image/3.jpg){#fig:003 width=90%}

Шаг 6 - (рис. [-@fig:004]). Он не может найти пакет, поэтому проблема не в команде, а, скорее всего, в соединении.

![2.2 Шаг 6](image/4.jpg){#fig:004 width=90%}

Шаг 8 - (рис. [-@fig:005]). Это было рассказано и показано в видео курса.

![2.2 Шаг 8](image/5.jpg){#fig:005 width=90%}

3. Часть "Запуск приложений". Здесь 4 задания.

Шаг 4 - (рис. [-@fig:006]). Это два самых логичных варианта.

![2.3 Шаг 4](image/6.jpg){#fig:006 width=90%}

Шаг 6 - (рис. [-@fig:007]). Интуитивно понятно, что третий вариант не подходит.

![2.3 Шаг 6](image/7.jpg){#fig:007 width=90%}

Шаг 7 - (рис. [-@fig:008]). Для этого задания я посмотрела официальную справку на сайте.

![2.3 Шаг 7](image/8.jpg){#fig:008 width=90%}

Шаг 8 - (рис. [-@fig:009]).

![2.3 Шаг 8, формулировка задания](image/9.jpg){#fig:009 width=90%}

Скрин поиска опции в справке - (рис. [-@fig:010])

![2.3 Шаг 8, поиск опции в справке](image/10.jpg){#fig:010 width=90%}

4. Часть "Контроль запускаемых программ". Здесь 4 задания.

Шаг 5 - (рис. [-@fig:011]). Первая программа была остановлена, а вторая приостановлена, поэтому информация только о второй и третьей, первая завершилась.

![2.4 Шаг 5](image/11.jpg){#fig:011 width=90%}

Шаг 8 - (рис. [-@fig:012]). Об этом было рассказано в материале курса.

![2.4 Шаг 8](image/12.jpg){#fig:012 width=90%}

Шаг 10 - (рис. [-@fig:013]). Мгновенно, значит -9

![2.4 Шаг 10](image/13.jpg){#fig:013 width=90%}

Шаг 11 - (рис. [-@fig:014]). Потому что сейчас процесс приостановлен.

![2.4 Шаг 11](image/14.jpg){#fig:014 width=90%}

5. Часть "Многопоточные приложения". Здесь 5 заданий.

Шаг 7 - (рис. [-@fig:015]). Процесс остановлен, значит он не использует процессор.

![2.5 Шаг 7](image/15.jpg){#fig:015 width=90%}

Шаг 8 - (рис. [-@fig:016]). Столько же, так как приложение сохраняет свое состояние, иначе нельзя было бы возобновить работу.

![2.5 Шаг 8](image/16.jpg){#fig:016 width=90%}

Шаг 9 - (рис. [-@fig:017]). Один из потоков нельзя остановить.

![2.5 Шаг 9](image/17.jpg){#fig:017 width=90%}

Шаг 12 - (рис. [-@fig:018]). Немного некорректный вопрос. Сейчас и build уже многопоточный.

![2.5 Шаг 12](image/18.jpg){#fig:018 width=90%}

Шаг 13 - (рис. [-@fig:019]). Я проделала все действия и прикрепила файл.

![2.5 Шаг 13](image/19.jpg){#fig:019 width=90%}

6. Часть "Менеджер терминалов tmux". Здесь 6 заданий.

Шаг 5 - (рис. [-@fig:020]). Он точно никуда не переместится и не вернется к работе.

![2.6 Шаг 5](image/20.jpg){#fig:020 width=90%}

Шаг 10 - (рис. [-@fig:021]). Это так, я проверила.

![2.6 Шаг 10](image/21.jpg){#fig:021 width=90%}

Шаг 14 - (рис. [-@fig:022]). Соединение прервется, но сервер продолжит работать, поэтому и tmux продолжит работать.

![2.6 Шаг 14](image/22.jpg){#fig:022 width=90%}

Шаг 15 - (рис. [-@fig:023]). Это самый логичный вариант ответа.

![2.6 Шаг 15](image/23.jpg){#fig:023 width=90%}

Шаг 18 - (рис. [-@fig:024]). Я изучила справку, это ","

![2.6 Шаг 18](image/24.jpg){#fig:024 width=90%}

Шаг 19 - (рис. [-@fig:025]). Я поделила на вкладки самостоятельно, а затем выбрала подходящие ответы.

![2.6 Шаг 19](image/25.jpg){#fig:025 width=90%}

# Выводы

Был полностью завершен второй раздел внешнего курса.
