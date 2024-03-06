---
## Front matter
title: "Отчет по лабораторной работе 2."
subtitle: "Первоначальная настройка git"
author: "Зайцева Пелагея Евгеньевна"

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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.



# Теоретическое введение

Системы контроля версий (Version Control System, VCS) применяются при работе нескольких человек над одним проектом. Обычно основное дерево проекта хранится в локальном или удалённом репозитории, к которому настроен доступ для участников проекта. При внесении изменений в содержание проекта система контроля версий позволяет их фиксировать, совмещать изменения, произведённые разными участниками проекта, производить откат к любой более ранней версии проекта, если это требуется.

    Система контроля версий Git представляет собой набор программ командной строки. Доступ к ним можно получить из терминала посредством ввода команды git с различными опциями.
    Благодаря тому, что Git является распределённой системой контроля версий, резервную копию локального хранилища можно сделать простым копированием или архивацией.



# Выполнение лабораторной работы

1. Установка программного обеспечения.

![рис.1](image/l2sk1.png){#fig:001 width=70%}

2. зададим имя и email владельца репозитория с помощью команд.

![рис.2](image/l2sk2.png){#fig:002 width=70%}

3. создадим ключи SSH и pgp.

![рис.3](image/l2sk3.png){#fig:003 width=70%}

4. добавим PGP ключа в GitHub.

![рис.4](image/l2sk4.png){#fig:004 width=70%}

5. Настроим автоматические подписи коммитов git.

![рис.5](image/l2sk5.png){#fig:005 width=70%}

6. создадим репозиторий курса на основе шаблона.

![рис.6](image/l2sk6.png){#fig:006 width=70%}

7. Настройка каталога курса.

![рис.7](image/l2sk7.png){#fig:007 width=70%}

# Выводы

Изучила идеологию и применение средств контроля версий.
Освоила умения по работе с git.


# Список литературы{.unnumbered}

::: {#refs}
:::
