---
## Front matter
title: "Отчет по лабораторной работе №2"
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

Целью работы является изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.


# Выполнение лабораторной работы
Создала учётную запись на сайте https://github.com/ и заполнила основные данные.

![Создание учетной записи на github](image/2.1.jpg){#fig:001 width=70%}

Выполнила базовую настройку git.

![Настройка git](image/2.2.jpg){#fig:001 width=70%}

Создала SSH ключ. 

![Создала SSH ключ](image/2.3.jpg){#fig:001 width=70%}

Скопировав из локальной консоли ключ в буфер обмена, вставила ключ в появившееся на сайте поле и указала для ключа имя (Title).
![Выполнение операций с ключом](image/2.4.jpg){#fig:001 width=70%}

С помощью терминала создала каталог для предмета «Архитектура компьютера».
![Создание каталога](image/2.5.jpg){#fig:001 width=70%}

Создала репозиторий на основе шаблона через web-интерфейс github.
![Создание репозитория](image/2.6.jpg){#fig:001 width=70%}

Далее сделала клонирование репозитория.
![Клонирование репозитория](image/2.7.jpg){#fig:001 width=70%}

# Задания для самостоятельной работы
Создала отчет третьей лабораторной работы в каталоге рабочего пространства.
![Создание отчета](image/2.8.jpg){#fig:001 width=70%}

Загрузила первую и вторую лабораторные работы на github.
![Загрузка работ на github](image/2.9.jpg){#fig:001 width=70%}


# Выводы

Изучили основные команды git, научились их применять. Cоздали иерархию рабочего пространства в локальном репозитории и на странице github.
