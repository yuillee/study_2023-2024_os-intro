---
## Front matter
title: "Отчет по выполнению индивидуального проекта"
subtitle: "Этап2"
author: "Зайцева Пелагея"

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

Добавить данные о себе на сайт.

# Задание

1. Добавить данные

2. Сделать пост о прошедшей неделе.

3. Добавить пост на тему по выбору.


# Выполнение лабораторной работы

1. Разместила фотографию автора сайта (свою).

![Рис.1](i2sk1.jpg){#fig:001 width=70%}

2. Разместила краткое описание автора.

![Рис.2](i2sk2.jpg){#fig:002 width=70%}

3. Добавила информацию о интересах и образовании.

![Рис.3](i2sk3.jpg){#fig:003 width=70%}

4. Создала пост по прошедшей неделе.

![Рис.4](i2sk4.jpg){#fig:004 width=70%}

5. Добавила пост на тему:

![Рис.5](i2sk5.jpg){#fig:005 width=70%}

6. Отправила все файлы на Git.

![Рис.6](i2sk6.jpg){#fig:006 width=70%}

# Выводы

Добавила все данные о себе на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
