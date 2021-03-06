---
# Front matter
lang: ru-RU
title: "Индивидуальный проект. Этап 3"
subtitle: "Редактирование информации о себе."
author: "Абдулфазов Мансур али оглы"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Цель работы

Добавить к сайту еще больше данные о себе. Добавить пост на тему: "LaTeX."

# Выполнение лабораторной работы

1. Добавить информацию о навыках (Skills).

Необходимо зайти в файл `content/home/skills.md` и изменить там данные (рис. 1).

![Информация о навыках](./images_prj03/1.png){ #fig:001 width=90% }

2. Добавить информацию об опыте (Experience).

Необходимо зайти в файл `content/home/experience.md` и изменить там данные (рис. 2).

![Информация об опыте](./images_prj03/2.png){ #fig:002 width=90% }


3. Сделать пост по прошедшей неделе. (рис. 4)

![Пост по прошедшей неделе](./images_prj03/3.png){ #fig:004 width=90% }

4. Добавить пост на тему: LaTeX (рис. 5)

![Пост LaTeX](./images_prj03/4.png){ #fig:005 width=90% }


# Вывод

Добавил данные об опыте, достижениях и навыках. Сделал пост по прошедшей неделе. Сделал пост на тему LaTeX.
