---
## Front matter
title: "Лабораторная работа №14"
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

Приобретение практических навыков работы с именованными каналами.


# Выполнение лабораторной работы

Изучив приведённые в тексте программы server.c и client.c. Взяв данные примеры
за образец, мы написали аналогичные программы, внеся следующие изменения:
1.Работает не 1 клиент, а несколько (например, два).
2.Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используем функцию sleep() для приостановки работы клиента.
3.Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Используем функцию clock() для определения времени работы сервер

1. Создадим файлы(рис. @fig:001).

![Создаем файлы](image/1.png){#fig:001 width=90%}

2. Напишем преобразованные программы в файлы (рис. @fig:002).

![файл common.h](image/2.png){#fig:002 width=90%}

![файл server.c](image/3.png){#fig:003 width=90%}

![файл Makefile](image/4.png){#fig:004 width=90%}

3. Скомпилируем файлы и проверим что вышло (рис. @fig:005).

![make all](image/5.png){#fig:005 width=90%}

![make all](image/6.png){#fig:006 width=90%}

4. Проверим работу программ (рис. @fig:007).

![Выполнение программ](image/7.png){#fig:007 width=90%}
# Выводы

Мы приобрели практические навыки работы с именованными каналами

# Список литературы{.unnumbered}

::: {#refs}
:::
