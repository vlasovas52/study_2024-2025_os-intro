---
## Front matter
title: "Отчет по лабораторной работе 9"
subtitle: "Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Задание

Выполнить последовательность комманд по заданному сценарию.


# Выполнение лабораторной работы 9.

Просмотр справки Midnight Commander. (рис. @fig:001).

![Справка](image/1.png){#fig:001 width=70%}

Система Midnight Commander. (рис. @fig:002).

![Midnight Commander](image/2.png){#fig:002 width=70%}

Выделение файлов. (рис. @fig:003).

![Выделение файлов](image/3.png){#fig:003 width=70%}

Копирование файлов. (рис. @fig:004).

![Копирование файлов](image/4.png){#fig:004 width=70%}

Просмотр информации по файлу. (рис. @fig:005).

![Просмотр информации по файлу](image/5.png){#fig:005 width=70%}

Просмотр информации по файлу с помощью Midnight Commander. (рис. @fig:006).

![Midnight Commander информация по файлу или каталогу](image/6.png){#fig:006 width=70%}

Редактор Midnight Commander(рис. @fig:007).

![Редактор Midnight Commander](image/7.png){#fig:007 width=70%}

Редактирование файла без сохранения(рис. @fig:008).

![Редактирование файла](image/8.png){#fig:008 width=70%}	

Создание нового каталога(рис. @fig:009).

![Создание каталога](image/9.png){#fig:009 width=70%}

Копирование каталога(рис. @fig:010).

![Копирование каталога](image/10.png){#fig:010 width=70%}

Поиск файла. (рис. @fig:011).

![Поиск файла](image/11.png){#fig:011 width=70%}

Дерево каталогов и перемещние в домашний каталог. (рис. @fig:012).

![Дерево каталогов](image/12.png){#fig:012 width=70%}

Файл меню. (рис. @fig:013)

![Файл меню](image/13.png){#fig:013 width=70%}

Файл расширений. (рис. @fig:014).

![Файл расширений](image/14.png){#fig:014 width=70%}

Настройки mc(внешний вид). (рис. @fig:015).

![Настройки mc](image/15.png){#fig:015 width=70%}

Создание текстового файла. (рис. @fig:016).

![Текстовый файл](image/16.png){#fig:016 width=70%}

Удаление строки. (рис. @fig:017).

![До удаления](image/17.png){#fig:017 width=70%}

![После удаления](image/18.png){#fig:018 width=70%}

Копирование строк(рис. @fig:019).

![До копирования](image/19.png){#fig:019 width=70%}

![После копирования](image/20.png){#fig:020 width=70%}

Перемещение строк(рис. @fig:021).

![Перемещение строк](image/21.png){#fig:021 width=70%}

Сохранение файла(рис. @fig:022).

![Сохранение файла](image/22.png){#fig:022 width=70%}

Отключение подстветки синтаксиса(рис. @fig:023).

![До отключения](image/23.png){#fig:023 width=70%}

![После отключения](image/24.png){#fig:024 width=70%}


# Выводы

Мы освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Список литературы{.unnumbered}

::: {#refs}
:::
