---
## Front matter
title: "Отчет по лабораторной работе 6"
subtitle: "Основы интерфейса взаимодействия
пользователя с системой Unix на уровне командной строки"
author: "Власов Артем Сергеевич"

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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Задание

Выполнить последовательность комманд по заданному сценарию для ознакомления с элементами командой строки.


# Выполнение лабораторной работы 6.

Открываем коммандную строку и выводим на экран путь к домашнему каталогу. (рис. @fig:001).

![Использование комманды pwd](image/1.png){#fig:001 width=70%}

Переходим в папку temp. (рис. @fig:002).

![Переходим в папку temp](image/2.png){#fig:002 width=70%}

Реализуем просмотр содержимого папки с помощью комманды ls и дополнительных аргументов. (рис. @fig:003).

![Выводим содержимое каталога](image/3.png){#fig:003 width=70%}

![Используем аргументы -a -l -F](image/4.png){#fig:004 width=70%}

Переходим в каталог /var/spool и проверяем наличие папки cron. (рис. @fig:005).

![проверка наличия каталога cron](image/5.png){#fig:005 width=70%}

Переходим в домашний каталог и смотрим расширенную информацию о всех файлах и подкаталогах. (рис. @fig:006).

![Просмотр файлов домашнего каталога](image/6.png){#fig:006 width=70%}

Создание каталогов с помощью mkdir. (рис. @fig:007).

![Создание каталога](image/7.png){#fig:007 width=70%}

![Создание подкаталога](image/8.png){#fig:008 width=70%}

![Создание и удаление трех каталогов одной коммандой](image/9.png){#fig:009 width=70%}

Использование rm и rmdir. (рис. @fig:010).

![Попытка удаления кталога с помощью rm](image/10.png){#fig:010 width=70%}

![Удаление каталога с помощью rmdir](image/11.png){#fig:011 width=70%}

Рекурсивный вывод всех подкаталогов. (рис. @fig:012).

![использование параметра -R](image/12.png){#fig:012 width=70%}

Вывод содержимог, отсортированного по времени с подробной информацией. (рис. @fig:013).

![Использование -tl](image/13.png){#fig:013 width=70%}

Информация о cd. (рис. @fig:014).

![Man cd](image/14.png){#fig:014 width=70%}

Информация о pwd. (рис. @fig:015).

![Man pwd](image/15.png){#fig:015 width=70%}

Информация о mkdir. (рис. @fig:016).

![Man mkdir](image/16.png){#fig:016 width=70%}

Информация о rmdir. (рис. @fig:017).

![Man rmdir](image/17.png){#fig:017 width=70%}

Информация о rm. (рис. @fig:018).

![Man rm](image/18.png){#fig:018 width=70%}

История вводы командной строки. (рис. @fig:019).

![History](image/19.png){#fig:019 width=70%}

Создание подкаталога путем модификации комманды из истории. (рис. @fig:020).

![Модификация комманды из history](image/20.png){#fig:020 width=70%}


# Выводы

Мы получили практические навыки работы c коммандной строкой. Научились пользоваться различными инструментами для создания, удаления и просмотра каталогов, ознакомились с параметрами комманд.

# Список литературы{.unnumbered}

::: {#refs}
:::
