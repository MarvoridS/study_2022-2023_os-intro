---
## Front matter
title: "Индивидуальный отчет"
subtitle: "Операционные системы"
author: "Сабралиева Марворид Нуралиевна"

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

Заполнить на сайте информацию о себе

# Задание
Список добавляемых данных.

    Разместить фотографию владельца сайта.
    Разместить краткое описание владельца сайта (Biography).
    Добавить информацию об интересах (Interests).
    Добавить информацию от образовании (Education).

Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
-Управление версиями. Git.


# Выполнение лабораторной работы

1. Размещаем фотографию владельца сайта,краткое описание владельца сайта, информацию об интересах и образовании

![Добавили имя](image/1.png){#fig:001 width=90%}


![Добавляем фотографию](image/2.png){#fig:002 width=90%}


![Информация об образовании](image/3.png){#fig:003 width=90%}


![Информация об интересах](image/4.png){#fig:004 width=90%}

2. Делаем пост по прошедшей неделе (рис. @fig:008) (рис. @fig:009)


![файл md](image/8.png){#fig:008 width=90%}


![сайт](image/9.png){#fig:009 width=90%}


3. Делаем пост на тему " Управление версиями. Git." (рис. @fig:010) (рис. @fig:011)

![сайт](image/10.png){#fig:010 width=90%}


![файл md](image/11.png){#fig:011 width=90%}



# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
