---
## Front matter
lang: ru-RU
title: 1 этап и ндивидуальный проект
subtitle: Операционные системы
author:
  - Норсоян Шушаник Гагиковна
institute:
  - Российский университет дружбы народов, Москва, Россия 22 февраля 2023

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
  * студент направления Бизнес-информатика
  * Российский университет дружбы народов
  * [shushaniknorsoian@gmail.com]
  * <https://github.com/shushaaaa/shushaaaa.github.io>
:::
::::::::::::::

# Вводная часть

## Объект и предмет исследования

- Презентация как текст
- Программное обеспечение для создания презентаций
- Входные и выходные форматы презентаций


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

## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты

## Цели и задачи

Загрузка шаблона сайта на репозиторий и githab и синхронизация сайта с githab.

## Содержание исследования

1. Устанавливаем необходимое программное устройство  (рис. [-@fig:001])

![установка программного устройства](image/скрин11.png){#fig:001 width=90%}

##

2. Использую команду ~/bin/hugo, чтобы скопировать ссылку на сайт  (рис. [-@fig:002])

![копирование ссылки на сайт](image/1.png){#fig:002 width=90%}

##

3. Далее перехожу в гитхаб и создаю еще один репозиторий  (рис. [-@fig:003])

![создание репозитория](image/22.png){#fig:003 width=90%}

##

4. Клонируем данный репозиторий  (рис. [-@fig:004])

![клонирование репозитория](image/скрин1.png){#fig:004 width=90%}

##

5. Переключаюсь на новую ветку и ввожу команды get add, git commit -am, git push (рис. [-@fig:005])

![новая ветка](image/2.png){#fig:005 width=90%}

##

6. Далее клонируем и в папке гитигнор комментируем public и теперь в нашей папке есть файл README.md

![клонирование ветки](image/3.png){#fig:006 width=90%}

##

![файл README.md](image/33.png){#fig:007 width=90%}

##

7. с помомощью команды бин hugo автоматически сгенирируем папки в репозиторий и синхронизируем их

![команда hugo](image/4.png){#fig:008 width=90%}

##

![синхронизация ](image/5.png){#fig:009 width=90%}

##

![синхронизация](image/6.png){#fig:010 width=90%}

##

8. обновляем репозиторий и видим появившиеся папки

![новые папки и файлы](image/7.png){#fig:011 width=90%}

## Результаты

Мы научились загружать шаблон сайта на репозиторий и github и синхронизтровать сайт с github.


## Итоговый слайд

- Запоминается последняя фраза. © Штирлиц
:::

