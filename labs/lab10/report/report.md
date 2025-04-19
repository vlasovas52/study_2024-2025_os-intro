---
## Front matter
title: "Отчет по лабораторной работе 10"
subtitle: "Текстовый редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

Выполнить последовательность действий по заданному сценарию.


# Выполнение лабораторной работы 10.

СОздание и откртие файла в vi. (рис. @fig:001).

![Создание калагога и открытие файла с помощью vi](image/1.png){#fig:001 width=70%}

Вставка текста в файл с помощью vi. (рис. @fig:002).

![Вставка текста в файл](image/2.png){#fig:002 width=70%}

Запись и выход из файла. (рис. @fig:003).

![Сохранение изменений](image/3.png){#fig:003 width=70%}

Делаем файл исполняемым. (рис. @fig:004).

![Изменение доступа на исполнение](image/4.png){#fig:004 width=70%}

Открытие файла в vi. (рис. @fig:005).

![Открываем файл](image/5.png){#fig:005 width=70%}

Пишем HELLO вместо HELL. (рис. @fig:006).

![Изменение файла](image/6.png){#fig:006 width=70%}

Удаляем слово LOCAL(рис. @fig:007).

![Удаляем слово LOCAL](image/7.png){#fig:007 width=70%}

Пишем вмсето него local(рис. @fig:008).

![Пишем вмсето него local](image/8.png){#fig:008 width=70%}	

Переходим на последнюю строчку и пишем после нее еще одну(рис. @fig:009).

![Добавление строки после заданной](image/9.png){#fig:009 width=70%}

Удаление созданной строки(рис. @fig:010).

![Удаление строки](image/10.png){#fig:010 width=70%}

Отмена предыдущего действия(клавиша u). (рис. @fig:011).

![Отмена предыдущего действия](image/11.png){#fig:011 width=70%}

Сохранение изменений. (рис. @fig:012).

![Сохранение изменений](image/3.png){#fig:012 width=70%}


# Выводы

Мы освоили основные возможности текстового редактора vi, научились выполнять действия, используя горячие клавиши.

# Список литературы{.unnumbered}

::: {#refs}
:::
