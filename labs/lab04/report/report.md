---
## Front matter
title: "Отчет по лабораторной работе 4"
subtitle: "Продвинутое использование git"
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

Получение навыков правильной работы с репозиториями git.

# Задание


Выполнить работу для тестового репозитория.

Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.


# Выполнение лабораторной работы 4.

Устанавливаем gitflow. (рис. @fig:001).

![Установка gitflow](image/1.png){#fig:001 width=70%}

![Установка gitflow](image/2.png){#fig:002 width=70%}

Устанавливаем nodejs. (рис. @fig:003).

![Устанавливаем nodejs](image/3.png){#fig:003 width=70%}

![Устанавливаем pnpm](image/4.png){#fig:004 width=70%}

Настройка nodejs. (рис. @fig:005).

![Запускаем pnpm](image/5.png){#fig:005 width=70%}

![Установка программы для помощи в форматировании коммитов](image/6.png){#fig:006 width=70%}

![Установка программы для помощи в создании логов](image/7.png){#fig:007 width=70%}

Создание и первый коммит в репозиторий git(рис. @fig:008).

![Переделываю gpg key и делаю первый коммит](image/8.png){#fig:008 width=70%}

![Переделываю gpg key и делаю первый коммит](image/9.png){#fig:009 width=70%}

![Переделываю gpg key и делаю первый коммит](image/10.png){#fig:010 width=70%}

Конфигурация общепринятных коммитов. (рис. @fig:011).

![Конфигурация пакетов nodejs](image/11.png){#fig:011 width=70%}

![Редактирование файла пакета](image/12.png){#fig:012 width=70%}

![Редактирование файла пакета](image/13.png){#fig:013 width=70%}

![Добавляем новые файлы](image/14.png){#fig:014 width=70%}

Конфигурация gitflow(рис. @fig:015).

![Инициализация gitflow](image/15.png){#fig:015 width=70%}

![Проверка ветки, в которой нахожусь](image/16.png){#fig:016 width=70%}

Создание релиза 1.0.0 (рис. @fig:017).

![Создание релиза и журнала изменений](image/17.png){#fig:017 width=70%}

![Добавление журнала изменений в индекс и залив релиза в основную ветку](image/18.png){#fig:018 width=70%}

![Отправка файлов и сохранение релиза на github](image/19.png){#fig:019 width=70%}

Создание релиза 1.2.3(рис. @fig:020).
![Создаем релиз и изменяем версию пакета](image/20.png){#fig:020 width=70%}

![Добавляем журнал изменений](image/23.png){#fig:021 width=70%}

![Заливаем релизную ветку в основную](image/21.png){#fig:022 width=70%}

![Отправляем изменения на сервер](image/22.png){#fig:023 width=70%}

![Создаем релиз на github](image/24.png){#fig:024 width=70%}

Проверка (рис. @fig:025).

![Релиз 1.0.0 на github](image/25.png){#fig:025 width=70%}

![Релиз 1.2.3 на github](image/26.png){#fig:026 width=70%}

# Выводы

Мы научились работать с gitflow, пакетами, конфигами и логами. Преобразовали тестовый репозиторий в репозиторий с gitflow. Научились работать с релизами.

# Список литературы{.unnumbered}

::: {#refs}
:::
