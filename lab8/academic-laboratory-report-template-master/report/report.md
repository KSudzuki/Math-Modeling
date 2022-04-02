---
# Front matter
title: "Лабораторная работа №8"
subtitle: "Модель конкуренции двух фирм"
author: "Ким Илья Владиславович"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
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
## Misc options
indent: true
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

Научиться строить модель конкуренции двух фирм.

# Задание

![](image/1.jpg){ #fig:001 width=70% }

![](image/2.jpg){ #fig:002 width=70% }

![](image/3.jpg){ #fig:003 width=70% }

# Теоретическое введение

![](image/4.jpg){ #fig:004 width=70% }

![](image/5.jpg){ #fig:005 width=70% }

![](image/6.jpg){ #fig:006 width=70% }

![](image/7.jpg){ #fig:007 width=70% }

![](image/8.jpg){ #fig:008 width=70% }

![](image/9.jpg){ #fig:009 width=70% }

![](image/10.jpg){ #fig:010 width=70% }

![](image/11.jpg){ #fig:011 width=70% }

![](image/12.jpg){ #fig:012 width=70% }

![](image/13.jpg){ #fig:013 width=70% }

![](image/14.jpg){ #fig:014 width=70% }

# Выполнение лабораторной работы

1. Случай 1:

![](image/15.jpg){ #fig:015 width=70% }

Код программы: 

![](image/16.jpg){ #fig:016 width=70% }

График:

![](image/17.jpg){ #fig:017 width=70% }

2. Случай 2:

![](image/18.jpg){ #fig:018 width=70% }

Код программы:

![](image/19.jpg){ #fig:019 width=70% }

График:

![](image/20.jpg){ #fig:020 width=70% }

# Выводы

Научились строить модель конкуренции двух фирм.

