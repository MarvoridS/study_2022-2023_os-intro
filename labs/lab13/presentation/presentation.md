---
## Front matter
lang: ru-RU
title: Лабораторная работа №13
subtitle: Операционные системы
author:
  - Сабралиева М. Н.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Сабралиева Марворид Нуралиевна
  * студентка НБИбд-02-22 кафедры прикладной информатики и теории вероятностей
  * Российский университет дружбы народов
:::
::::::::::::::

# Создание презентации

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
## Цели и задачи

- Приобрести простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями

## Содержание исследования

1. В домашнем каталоге создадим подкаталог ~/work/os/lab_prog. 

![Создание подкаталога](image/1.png){#fig:001 width=90%}

##

2. Создадим в нём файлы: calculate.h, calculate.c, main.c.
Это будет примитивнейший калькулятор, способный складывать, вычитать, умножать
и делить, возводить число в степень, брать квадратный корень, вычислять sin, cos, tan. При запуске он будет запрашивать первое число, операцию, второе число. После этого программа выведет результат и остановится.

![Создание файлов](image/2.png){#fig:002 width=90%}

##

![Реализация функций калькулятора в файле calculate.h](image/3.png){#fig:003 width=90%}

##

![Интерфейсный файл calculate.h, описывающий формат вызова функции калькулятора](image/4.png){#fig:004 width=90%}

##

![Основной файл main.c, реализующий интерфейс пользователя к калькулятору](image/5.png){#fig:005 width=90%}

##

3. Выполните компиляцию программы посредством gcc 

![компиляция программы](image/6.png){#fig:006 width=90%}

##

4. Создадим Makefile и с помощью gdb выполним отладку программы calcul

![запустим отладчик](image/7.png){#fig:007 width=90%}

##

![запуск программы](image/8.png){#fig:008 width=90%}

##

5. С помощью утилиты splint попробуйте проанализировать коды файлов calculate.c
и main.c. 

![утилита splint](image/9.png){#fig:009 width=90%}

## Результаты

- В ходе выполнения лабораторной работы я приобрела простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования калькулятора с простейшими функциям

## Итоговый слайд

- Запоминается последняя фраза. © Штирлиц

:::

