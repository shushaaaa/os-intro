---
## Front matter
lang: ru-RU
title: Лаборатрная рабта №2
subtitle: Простейший шаблон
author:
  - Норсоян Шушаник
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 17 февраля 2023

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

  * Норсоян Шушаник Гагиковна
  * студентка группы НБИбд-02-22
  * Российский университет дружбы народов


:::
::::::::::::::

# Вводная часть

## Актуальность

Лабораторная работа актуальна для тех, кто желаем освоить GitHub.

## Объект и предмет исследования

- Презентация как текст
- Программное обеспечение для создания презентаций
- Входные и выходные форматы презентаций

## Цели и задачи

- Изучить идеологию и применение средств контроля версий.
- Освоить умения по работе с git.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Результаты

## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты
.

## Содержание исследования

1. Базовая настройка git. (рис. [-@fig:001]) 

![терминал ](image/1.png){#fig:001 width=90%}

![терминал ](image/2.png){#fig:002 width=90%}

##

2. Я настроила вывод git (рис. [-@fig:003]) 

![терминал ](image/3.png){#fig:003 width=90%}

![терминал ](image/4.png){#fig:004 width=90%}

##

3. Я создала и сделала pgp ключ. SSH был настроен в прошлой лаболаторной (рис. [-@fig:005]) 

![терминал ](image/5.png){#fig:005 width=90%}

![терминал ](image/6.png){#fig:006 width=90%}

![гитхаб ](image/7.png){#fig:007 width=90%}

##

4. Я создала репозиторий для работы (рис. [-@fig:008]) 

![гитхаб ](image/8.png){#fig:008 width=90%}

![гитхаб ](image/9.png){#fig:009 width=90%}

##

5. Я прокоммитила и отправила файлы на гитхаб (рис. [-@fig:010])

![терминал ](image/10.png){#fig:010 width=90%}

![гитхаб ](image/11.png){#fig:011 width=90%}

## Результаты

- Настроили GitHub 
- Создали ключи

## Итоговый слайд

- В ходе выполнения лабораторной работы, мы изучили идеологию и применение средств контроля версий и освоили умения работать с git.



