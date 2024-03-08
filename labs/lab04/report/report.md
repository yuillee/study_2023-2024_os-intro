---
## Front matter
title: "Лабораторная работа 4"
subtitle: "Продвинутое использование git"
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

Получение навыков правильной работы с репозиториями git.


# Теоретическое введение
Рабочий процесс Gitflow Workflow. Будем описывать его с использованием пакета git-flow.                                        |

    Gitflow Workflow опубликована и популяризована Винсентом Дриссеном.
    Gitflow Workflow предполагает выстраивание строгой модели ветвления с учётом выпуска проекта.
    Данная модель отлично подходит для организации рабочего процесса на основе релизов.
    Работа по модели Gitflow включает создание отдельной ветки для исправлений ошибок в рабочей среде.
    Последовательность действий при работе по модели Gitflow:
        Из ветки master создаётся ветка develop.
        Из ветки develop создаётся ветка release.
        Из ветки develop создаются ветки feature.
        Когда работа над веткой feature завершена, она сливается с веткой develop.
        Когда работа над веткой релиза release завершена, она сливается в ветки develop и master.
        Если в master обнаружена проблема, из master создаётся ветка hotfix.
        Когда работа над веткой исправления hotfix завершена, она сливается в ветки develop и master.


# Выполнение лабораторной работы

1. Установка git-flow. Установка из коллекции репозиториев Copr 

![рис.1](image/l4sk1.jpg){#fig:001 width=70%}

2. Установка Node.js

![рис.2](image/l4sk2.jpg){#fig:002 width=70%}

3. Настройка Node.js

![рис.3](image/l4sk3.jpg){#fig:003 width=70%}

4. Общепринятые коммиты

4.1. Практический сценарий использования git

![рис.4](image/l4sk4.jpg){#fig:004 width=70%}

4.2. Конфигурим формат коммитов.

![рис.5](image/l4sk5.jpg){#fig:005 width=70%}

4.3 Конфигурация git-flow

![рис.6](image/l4sk6.jpg){#fig:006 width=70%}

# Выводы

Получила навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

::: {#refs}
:::









