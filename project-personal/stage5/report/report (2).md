---
## Front matter
title: "Отчет индивидуальный проект 5"
subtitle: "ИП 5 часть"
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

Добавить информацию о проектах, сделать пост по прошлой неделе и научный по выбору.

# Задание

Сделать 2 поста и проект.


# Выполнение 5 этапа.

Оформляем наш сайт как проект, находим картинку и вставляем ссылку на гит. (рис. @fig:001).

![Проект](image/1.png){#fig:001 width=70%}

Проверка раздела с проектом. (рис. @fig:002).

![Проверка](image/2.png){#fig:002 width=70%}

Пост по прошедшей неделе. (рис. @fig:003).

![Пост по прошедшей неделе](image/3.png){#fig:003 width=70%}

Пост на тему языки научного программирования. (рис. @fig:004).

![Пост на тему языки научного программирования](image/4.png){#fig:004 width=70%}

Проверка добавления наших постов. (рис. @fig:005).

![Проверка добавления наших постов](image/5.png){#fig:005 width=70%}

# Выводы

Мы добавили информацию о проектах и сделали 2 новых поста на сайте научного работника.

# Список литературы{.unnumbered}

::: {#refs}
:::
