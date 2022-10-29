---
# Front matter
title: "ЛАБОРАТОРНАЯ РАБОТА 4"
subtitle: "Язык разметки Markdown"
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Задание

1. В соответствующем каталоге сделайте отчёт по лабораторной работе No 3
в формате Markdown. В качестве отчёта необходимо предоставить отчёты
в 3 форматах: pdf, docx и md.
2. Загрузите файлы на github.

# Теоретическое введение

Архитектура ЭВМ
Чтобы вложить один список в другой, добавьте отступ для элементов дочер-
него списка:
- List item 1
- List item A
- List item B
- List item 2
Синтаксис Markdown для встроенной ссылки состоит из части [link text],
представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или
имени файла, на который дается ссылка:
[link text](file-name.md)
или
[link text](http://example.com/ "Необязательная подсказка")
Markdown поддерживает как встраивание фрагментов кода в предложение,
так и их размещение между предложениями в виде отдельных огражденных
блоков. Огражденные блоки кода — это простой способ выделить синтаксис для
фрагментов кода. Общий формат огражденных блоков кода:
``` language
your code goes in here
```

# Выполнение лабораторной работы

Здесь мы переходим к распакованному файлу и применяем команд"sudo perl./ install-tl --sin"
![Название рисунка](/home/gpgerra/Загрузки/1.png){ #fig:1}

Здесь мы устанавливаем Panok и pandok-CrossRef

![Название рисунка](/home/gpgerra/Загрузки/2.png){ #fig:2}

Переходим в каталог курса, сгенерированный во время 

![Название рисунка](/home/gpgerra/Загрузки/3.png){ #fig:3}

переходим в каталог курса, сгенерированный во время лабораторной работы 3, обновляем локальный репозиторий, применив команду "git pull". Затем мы переходим в каталог с шаблоном отчета lab4
![Название рисунка](/home/gpgerra/Загрузки/4.png){ #fig:4}

Реализация компиляции растенийс помощью команды "make" луэго абримослос архивос дженерадос, пересмотр задач,которые стоят перед вами, и применениекоманды "make clean" для устранения
![Название рисунка](/home/gpgerra/Загрузки/5.png){ #fig:5}

# Выводы

В настоящее время лаборатория, aprendemos a usar correctamente Markdown и TeX Live.

# Список литературы{.unnumbered}

::: {#refs}
:::
