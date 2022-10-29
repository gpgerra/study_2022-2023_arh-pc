---
# Front matter
title: "ЛАБОРАТОРНАЯ РАБОТА 3"
subtitle: "Система контроля версий Git"
author: "Герра Гарсия Паола Валентина"

## Generic otions
lang: ru-RU
toc-title: "gpgerra"

## Bibliography

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Целью работы является изучить идеологию и применение средств контроля
версий. Приобрести практические навыки по работе с системой git.

# Задание

1. Создайте отчет по выполнению лабораторной работы в соответствующем
каталоге рабочего пространства (labs>lab03>report).
2. Скопируйте отчеты по выполнению предыдущих лабораторных работ в
соответствующие каталоги созданного рабочего пространства.
3. Загрузите файлы на github.

# Теоретическое введение

Наиболее часто используемые команды git представлены в таблице

[-@tbl:std-dir] 

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Команда | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `git init`          | создание основного дерева репозитория                                                             |
| `git pull`      | получение обновлений (изменений) текущего дерева из центрального репозитория    |
| `git push`       | отправка всех произведённых изменений локального дерева в центральный репозиторий                                           |
| `git status`      | просмотр списка изменённых файлов в текущей директории |
| `git diff`     | просмотр текущих изменения                                                                      |
| `git add`      | добавить конкретные изменённые и/или созданные файлы
и/или каталоги 

# Выполнение лабораторной работы

Базовая настройка git 
![Название рисунка](/home/gpgerra/Загрузки/1(1).png){ #fig:1(1}

была выполнена настройка git, установлен utf-8, задано начальное (master) имя
ветки, также определены параметры autocrlf и safecrlf.

Создание SSh ключа 
![Название рисунка](/home/gpgerra/Загрузки/2(1).png){ #fig:2(1)}

Сгенерирована пара ключей (закрытый и открытый) 

![Название рисунка](/home/gpgerra/Загрузки/3(1).png){ #fig:3(1)}

С помощью команды cat вы скопировали ключ в буфер обмена 
![Название рисунка](/home/gpgerra/Загрузки/4(1).png){ #fig:4(1)}

Скопированный ключ был вставлен в требуемое поле на github.
- Создание рабочей области на основе шаблона. 

![Название рисунка](/home/gpgerra/Загрузки/5(1).png){ #fig:5(1)}

- Создание репозитория курса на основе шаблона 
![Название рисунка](/home/gpgerra/Загрузки/6.png){ #fig:6 }

на github создал репозиторий с именем study_2022–2023_arh-pc 

![Название рисунка](/home/gpgerra/Загрузки/7.png){ #fig:7  }

я клонирую вновь созданный репозиторий с помощью команды gif clone-recursive
“link”.

# Выводы

идеология управления версиями была правильно усвоена, например, как
использовать команды git, и были разработаны практические методы работы с
системой git

# Список литературы{.unnumbered}

::: {#refs}
:::
