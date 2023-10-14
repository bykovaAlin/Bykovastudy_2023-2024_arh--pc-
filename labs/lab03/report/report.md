---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Дисциплина:Архитектура компьютера"
author: "Быкова Алина Александровна"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.


# Выполнение лабораторной работы 
Я открыла терминал, перешла в каталог курса свормированный при выполнении лабораторной работы №2. Ввела команду git pull (рис. @fig:001).

![Выполнение команды git pull](image/1.jpg){#fig:001 width=70%}

Перешла в каталог с шаблоном отчета по лабораторной работе № 3. Провела компиляцию шаблона с использованием Makefile (рис. @fig:002).

![Выполнение команды make](image/2.jpg){#fig:002 width=70%}

Проверила корректность выполнения команды. 

Удалила полученные файлы с использованием Makefile. Проверила,что все файлы были удалены (рис. @fig:003).

![Выполнение команды make clean](image/3.jpg){#fig:003 width=70%}

Открыла файл report.md c помощью текстового редактора. Внимательно изучила структуру этого файла (рис. @fig:004).

![Открыла файл report.md](image/4.jpg){#fig:004 width=70%}

Я заполнила отчет и скомпилировала  его с использованием Makefile. Загрузила файл на github.

# Выполнение заданий для самостоятельной работы

Перешла в каталог с отчетом по второй лабораторной работе (рис. @fig:001).
![Переход в каталог](image/5.jpg){#fig:001 width=70%}

Открыла файл с шаблоном отчета и заполнила его (рис. @fig:002).
![Заполнение шаблона для отчета](image/6.1.jpg){#fig:002 width=70%}

Отчет в трех форматах предоставлен. Загрузила файлы на github. 


# Выводы

Я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.
