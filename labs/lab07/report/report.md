---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Операционные системы"
author: "Сабралиева Марворид"

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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

1. Изучим информацию о mc, вызвав в командной строке man mc. (рис. @fig:001).

![man mc](image/1.png){#fig:001 width=90%}

2. Запустим из командной строки mc, изучим его структуру и меню. (рис. @fig:002).

![mc](image/2.png){#fig:002 width=90%}

3. Выполните несколько операций в mc, используя управляющие клавиши , операции с панелями; 

![Выделение/отмена выделения](image/3.png){#fig:003 width=90%}

![Копирование](image/4.png){#fig:004 width=90%}

![Перемещение](image/5.png){#fig:005 width=90%}

![Данные о владельце](image/6.png){#fig:006 width=90%}

![Размер](image/7.png){#fig:007 width=90%}

4. Выполните основные команды меню левой (или правой) панели. Оцените степень подробности вывода информации о файлах.

![Данные](image/8.png){#fig:008 width=90%}

5. Используя возможности подменю Файл , выполните:

![просмотр содержимого текстового файла](image/9.png){#fig:009 width=90%}

![редактирование содержимого текстового файла](image/10.png){#fig:010 width=90%}

![создание каталога](image/11.png){#fig:011 width=90%}

![копирование в файлов в созданный каталог](image/12.png){#fig:012 width=90%}

6. С помощью соответствующих средств подменю Команда осуществите:

![поиск в файловой системе файла с заданными условиями](image/13.png){#fig:013 width=90%}

![выбор и повторение одной из предыдущих команд](image/14.png){#fig:014 width=90%}

![переход в домашний каталог](image/15.png){#fig:015 width=90%}

![анализ файла меню](image/15.png){#fig:015 width=90%}

![анализ файла расширений](image/16.png){#fig:016 width=90%}

1. Создайте текстовой файл text.txt.

![файл](image/17.png){#fig:017 width=90%}

2. Откройте этот файл с помощью встроенного в mc редактора.

![анализ файла](image/18.png){#fig:018 width=90%}

3. Вставьте в открытый файл небольшой фрагмент текста, скопированный из любого
другого файла или Интернета.

![анализ файла](image/19.png){#fig:019 width=90%}

4. Проделайте с текстом следующие манипуляции, используя горячие клавиши:

![Удалите строку текста](image/20.png){#fig:020 width=90%}

![Выделим фрагмент текста и скопируйте его на новую строку](image/21.png){#fig:021 width=90%}

Перейдите в конец файла (нажав комбинацию клавиш) и напишите некоторый
текст. Перейдите в начало файла (нажав комбинацию клавиш) и напишите некоторый
текст.

![](image/22.png){#fig:022 width=90%}

![сохраните и закройте файл.](image/23.png){#fig:023 width=90%}

# Выводы

Мы освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.


# Список литературы{.unnumbered}

::: {#refs}
:::
