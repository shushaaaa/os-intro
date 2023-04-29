---
## Front matter
title: "1 этап индивидуальный проект"
subtitle: "Операционные системы"
author: "Норсоян Шушаник Гагиковна"

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

Загрузка шаблона сайта на репозиторий и гит и синхронизация сайта с гит.

# Задание

Размещение на Github pages заготовки для персонального сайта.

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.


# Выполнение лабораторной работы

1. Установила необходимое программное устройство

![установка программного устройства](image/скрин11.png){#fig:001 width=90%}

2. Использую команду ~/bin/hugo, чтобы скопировать ссылку на сайт

![копирование ссылки на сайт](image/1.png){#fig:002 width=90%}

3. Далее перехожу в гитхаб и создаю еще один репозиторий

![создание репозитория](image/22.png){#fig:003 width=90%}

4. Клонируем данный репозиторий

![клонирование репозитория](image/скрин1.png){#fig:004 width=90%}

5. Переключаюсь на новую ветку и ввожу команды get add, git commit -am, git push

![новая ветка](image/2.png){#fig:005 width=90%}

6. Далее клонируем и в папке гитигнор комментируем public и теперь в нашей папке есть файл README.md

![клонирование ветки](image/3.png){#fig:006 width=90%}

![файл README.md](image/33.png){#fig:007 width=90%}

7. с помомощью команды бин hugo автоматически сгенирируем папки в репозиторий и синхронизируем их

![команда hugo](image/4.png){#fig:008 width=90%}

![синхронизация ](image/5.png){#fig:009 width=90%}

![синхронизация](image/6.png){#fig:010 width=90%}

8. обновляем репозиторий и видим появившиеся папки

![новые папки и файлы](image/7.png){#fig:011 width=90%}
# Выводы

Мы научились загружать шаблон сайта на репозиторий и гит и синхронизтровать сайт с гит.


# Список литературы{.unnumbered}

::: {#refs}
:::
