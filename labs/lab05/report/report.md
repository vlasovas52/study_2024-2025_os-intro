---
## Front matter
title: "Отчет по лабораторной работе 5"
subtitle: "Работа с рass и управление файлами конфигурации"
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

Получение навыков правильной работы с pass и chezmoi.

# Задание

Выполнить первичную установку и настройку pass и chezmoi. Проверить их работу на заднном сценарии.


# Выполнение лабораторной работы 5.

Устанавливаем pass и gopass. (рис. @fig:001).

![Установка pass и gopass](image/1.png){#fig:001 width=70%}

Проверяем наличие ключа gpg. (рис. @fig:002).

![Проверка ключа](image/2.png){#fig:002 width=70%}

Инициализируем хранилище. (рис. @fig:003).

![Инициализация хранилища](image/3.png){#fig:003 width=70%}

Синхронизация с git. (рис. @fig:004).

![Синхронизация с git](image/4.png){#fig:004 width=70%}

Создание и установка адреса репозитория. (рис. @fig:005).

![Установка адреса нового репозитория](image/5.png){#fig:005 width=70%}

Коммит изменений, сделанных в ручную. (рис. @fig:006).

![Коммит и отправка данных](image/6.png){#fig:006 width=70%}

![Проверка статуса синнхронизации](image/7.png){#fig:007 width=70%}

Установка плагина и интерфеса для взаимодействия browserpass(рис. @fig:008).

![Установка расширения для Firefox](image/8.png){#fig:008 width=70%}

![Установка интерцеса для взаимодействия](image/9.png){#fig:009 width=70%}

![Установка интерцеса для взаимодействия](image/10.png){#fig:010 width=70%}

Сохранение пароля для файла. (рис. @fig:011).

![Создание файла и добавление нового пароля](image/11.png){#fig:011 width=70%}

![Проверка пароля](image/12.png){#fig:012 width=70%}

![Изменение пароля на случайно сгенерированный](image/13.png){#fig:013 width=70%}

Установка дополнительного программного обеспечения для управления файлами конфигурации. (рис. @fig:014).

![Установка дополнительного программного обеспечения](image/14.png){#fig:014 width=70%}

![Подключение к каталогу шрифтов](image/15.png){#fig:015 width=70%}

![Поиск нужных шрифтов](image/16.png){#fig:016 width=70%}

![Установка шрифтов](image/17.png){#fig:017 width=70%}

Установка бинарного файла chezmoi (рис. @fig:018).

![Установка с помощью wget](image/18.png){#fig:018 width=70%}

Создание репозитория по шаблону(рис. @fig:018).

![Создание репозитория](image/19.png){#fig:019 width=70%}

Подключение репозитория к своей системе(рис. @fig:020).

![Подключаем репозиторий](image/20.png){#fig:020 width=70%}

![Проверка и подтверждение изменений изменений](image/21.png){#fig:021 width=70%}

Ежедневные операции с chezmoi(рис. @fig:022).

![Обновление chezmoi и извлечение последних изменений из репозитория](image/22.png){#fig:022 width=70%}

![Установка autoCommit и autoPush в файл конфигурации chezmoi](image/23.png){#fig:023 width=70%}

# Выводы

Мы получили практические навыки работы с pass и chezmoi. Проверили их работу на определенном сценарии на двух созданных репозиториях. Связали устройство и удаленный репозиторий на github c помощью pass и chezmoi.

# Список литературы{.unnumbered}

::: {#refs}
:::
