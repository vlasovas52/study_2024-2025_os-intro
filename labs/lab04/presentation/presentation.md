---
## Front matter
lang: ru-RU
title: Лабораторная работа 4
subtitle: Отчет
author:
  - Власов Артем Сергеевич
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 4 марта 2025

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

Получение навыков правильной работы с репозиториями git.

# Задание

Выполнить работу для тестового репозитория.

Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

                                                    
# Выполнение лабораторной работы 4.

## Устанавливаем gitflow.

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Установка gitflow](image/1.png){#fig:001 width=70%}

![Установка gitflow](image/2.png){#fig:002 width=70%}

:::
::::::::::::::


## Устанавливаем nodejs. 

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Устанавливаем nodejs](image/3.png){#fig:003 width=70%}

![Устанавливаем pnpm](image/4.png){#fig:004 width=70%}

:::
::::::::::::::


## Настройка nodejs.

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Запускаем pnpm](image/5.png){#fig:005 width=70%}

![Установка программы для помощи в форматировании коммитов](image/6.png){#fig:006 width=70%}

![Установка программы для помощи в создании логов](image/7.png){#fig:007 width=70%}
:::
::::::::::::::


## Создание и первый коммит в репозиторий git

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Переделываю gpg key и делаю первый коммит](image/8.png){#fig:008 width=70%}

![Переделываю gpg key и делаю первый коммит](image/9.png){#fig:009 width=70%}

:::
::::::::::::::


## Конфигурация общепринятных коммитов.

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Конфигурация пакетов nodejs](image/11.png){#fig:011 width=70%}

![Редактирование файла пакета](image/12.png){#fig:012 width=70%}

![Редактирование файла пакета](image/13.png){#fig:013 width=70%}

![Добавляем новые файлы](image/14.png){#fig:014 width=70%}

:::
::::::::::::::


## Конфигурация gitflow

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Инициализация gitflow](image/15.png){#fig:015 width=70%}

![Проверка ветки, в которой нахожусь](image/16.png){#fig:016 width=70%}

:::
::::::::::::::


## Создание релиза 1.0.0 

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Создание релиза и журнала изменений](image/17.png){#fig:017 width=70%}

![Добавление журнала изменений в индекс и залив релиза в основную ветку](image/18.png){#fig:018 width=70%}

![Отправка файлов и сохранение релиза на github](image/19.png){#fig:019 width=70%}

:::
::::::::::::::

## Создание релиза 1.2.3

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Создаем релиз и изменяем версию пакета](image/20.png){#fig:020 width=70%}

![Добавляем журнал изменений](image/23.png){#fig:021 width=70%}

:::
::::::::::::::


## Создание релиза 1.2.3

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Заливаем релизную ветку в основную](image/21.png){#fig:022 width=70%}

![Отправляем изменения на сервер](image/22.png){#fig:023 width=70%}

![Создаем релиз на github](image/24.png){#fig:024 width=70%}

:::
::::::::::::::



## Проверка

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Релиз 1.0.0 на github](image/25.png){#fig:025 width=70%}

:::
::::::::::::::


## Проверка

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![Релиз 1.2.3 на github](image/26.png){#fig:026 width=70%}

:::
::::::::::::::

## Выводы
Мы научились работать с gitflow, пакетами, конфигами и логами. Преобразовали тестовый репозиторий в репозиторий с gitflow. Научились работать с релизами.
