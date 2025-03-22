---
## Front matter
lang: ru-RU
title: Лабораторная работа 6
subtitle: Отчет
author:
  - Власов Артем Сергеевич
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 22 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Власов Артем Сергеевич
  * Группа НПИбд-01-24
  * Студент
  * Российский университет дружбы народов
  * [1132246841@pfur.ru](mailto:1132246841@pfur.ru)


## Цели и задачи

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Задание

Выполнить последовательность комманд по заданному сценарию для ознакомления с элементами командой строки.

                                                    
# Выполнение лабораторной работы 6.

## Открываем коммандную строку и выводим на экран путь к домашнему каталогу

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Использование комманды pwd](image/1.png){#fig:001 width=70%}

:::
::::::::::::::


## Переходим в папку temp

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Переходим в папку temp](image/2.png){#fig:002 width=70%}

:::
::::::::::::::


## Реализуем просмотр содержимого папки с помощью комманды ls и дополнительных аргументов

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Выводим содержимое каталога](image/3.png){#fig:003 width=70%}

![Используем аргументы -a -l -F](image/4.png){#fig:004 width=70%}

:::
::::::::::::::


## Переходим в каталог /var/spool и проверяем наличие папки cron.

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Проверка наличия каталога cron](image/5.png){#fig:005 width=70%}

:::
::::::::::::::


## Переходим в домашний каталог и смотрим расширенную информацию о всех файлах и подкаталогах

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Просмотр файлов домашнего каталога](image/6.png){#fig:006 width=70%}

:::
::::::::::::::


## Создание каталогов с помощью mkdir

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Создание каталога](image/7.png){#fig:007 width=70%}

![Создание подкаталога](image/8.png){#fig:008 width=70%}

![Создание и удаление трех каталогов одной коммандой](image/9.png){#fig:009 width=70%}

:::
::::::::::::::


## Использование rm и rmdir.

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Попытка удаления кталога с помощью rm](image/10.png){#fig:010 width=70%}

![Удаление каталога с помощью rmdir](image/11.png){#fig:011 width=70%}

:::
::::::::::::::

## Рекурсивный вывод всех подкаталогов

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Использование параметра -R](image/12.png){#fig:012 width=70%}

:::
::::::::::::::


## Вывод содержимог, отсортированного по времени с подробной информацией

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Использование -tl](image/13.png){#fig:013 width=70%}

:::
::::::::::::::



## Информация о cd

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Man cd](image/14.png){#fig:014 width=70%}

:::
::::::::::::::


## Информация о pwd

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Man pwd](image/15.png){#fig:015 width=70%}

:::
::::::::::::::


## Информация о mkdir

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Man mkdir](image/16.png){#fig:016 width=70%}

:::
::::::::::::::

## Информация о rmdir

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Man rmdir](image/17.png){#fig:017 width=70%}

:::
::::::::::::::

## Информация о rm

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Man rm](image/18.png){#fig:018 width=70%}

:::
::::::::::::::

## История вводы командной строки

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![History](image/19.png){#fig:019 width=70%}

![Модификация комманды из history](image/20.png){#fig:020 width=70%}

:::
::::::::::::::


## Выводы
Мы получили практические навыки работы c коммандной строкой. Научились пользоваться различными инструментами для создания, удаления и просмотра каталогов, ознакомились с параметрами комманд.
