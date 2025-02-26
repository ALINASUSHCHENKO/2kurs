---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1. Установка Kali Linux"
author: "Сущенко Алина Николаевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Установить на ViryualBox OC Kali linux и задать нужные для работы параметры.

# Выполнение лабораторной работы

Установим выбранную ОС в виртуальной машине (как указано по минимальным возмодным значениям). (рис. [-@fig:001]).

![Установка Kali linux](./image/11.png){#fig:001 width=70%}

Все настройки виртуальной машины. (рис. [-@fig:002]).

![Вид ОС в виртуальной машине](./image/12.png){#fig:002 width=70%}

После загрузки Kali предлагает настроить рабочее место через BIOS. (рис. [-@fig:003]).

![Вид BIOS в Kali](./image/13.png){#fig:003 width=70%}

В настройках нам предлагают выбрать язык, разметку диска, выбор программного обеспечения, GRUB boot loader и т.д (рис. [-@fig:004]).

![Экран выбора языка ](./image/4.png){#fig:004 width=70%}

Далее мы оставляем загружать нужные нам компоненты, параллельно выставляя параметры, о которых уже было сказано пунктом выше. (рис. [-@fig:005]).

![Экран загрузки компонентов](./image/5.png){#fig:005 width=70%}

После загрузки перезапустим виртуальную машину. Нас встречает экран рабочего стола. (рис. [-@fig:006]).

![Экран рабочего стола](./image/6.png){#fig:006 width=70%}

# Выводы

В течение выполнения данной работы нам удалось установить и проверить работу Kali в виртуальной машине.
