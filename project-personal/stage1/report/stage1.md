---
## Front matter
title: "отчет по 1 этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Клименко Алёна Сергеевна"

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

Размещение на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

скачиваем архив hugo с офиц репозитория (рис. [-@fig:001]).

![Установка go hugo](image/2.PNG){#fig:001 width=70%}

разархивируем файл и перенесем hugo в usr/local/bin (рис. [-@fig:002]).

![usr/local/bin](image/1.PNG){#fig:002 width=70%}

Создаем репозиторий на github. клонируем его создаем с помощью команды mkdir -p нужные нам папки и переносим туда hugo.yaml (рис. [-@fig:003]).

![Создание репозитория](image/3.PNG){#fig:003 width=70%}

вфгружаем и коммитим все (рис. [-@fig:004]).

![git add .](image/4.PNG){#fig:004 width=70%}

открываем шаблон сайта созданые на моем репозитории (рис. [-@fig:005]).

![Удаление каталога](image/5.PNG){#fig:005 width=70%}


# Выводы

Разместила на Github pages заготовки для персонального сайта.

