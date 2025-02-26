---
## Front matter
lang: ru-RU
title: Этап 1. Установка Kali Linux
subtitle: Индивидуальный проект
author:
  - А.Н. Сущенко
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 26 февраля 2025

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Сущенко Алина Николаевна
  * студентка НПИбд-01-23
  * Российский университет дружбы народов

:::
::: {.column width="30%"}

![](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/asn.jpg)

:::
::::::::::::::

# Вводная часть

## Актуальность

- Актуальность данной работы заключается в исследовании новой ОС Kali
- И работой с виртаульной машиной

## Объект и предмет исследования

- ОС Kali

## Цели и задачи

- Создать и настроить на своей виртуальной машине ОС Kali.
- Разобраться во внутренних настройках.
- Удостовериться в работе данной ОС.

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

# Элементы презентации

## Актуальность

- Актуальность данной работы заключается в исследовании новой ОС Kali
- И работой с виртаульной машиной

## Цели и задачи

- Создать и настроить на своей виртуальной машине ОС Kali.
- Разобраться во внутренних настройках.
- Удостовериться в работе данной ОС.

## Материалы и методы

- ОС Kali linux.
- VirtualBox

## Содержание исследования

Установим выбранную ОС в виртуальной машине (как указано по минимальным возмодным значениям).

![Установка Kali linux](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/11.png)

Все настройки виртуальной машины.

![Вид ОС в виртуальной машине](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/12.png)

После загрузки Kali предлагает настроить рабочее место через BIOS.

![Вид BIOS в Kali](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/13.png)

В настройках нам предлагают выбрать язык, разметку диска, выбор программного обеспечения, GRUB boot loader и т.д.

![Экран выбора языка ](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/14.png)

Далее мы оставляем загружать нужные нам компоненты, параллельно выставляя параметры, о которых уже было сказано пунктом выше.

![Экран загрузки компонентов](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/15.png)

После загрузки перезапустим виртуальную машину. Нас встречает экран рабочего стола.

![Экран рабочего стола](/home/ansuthenko/2kurs/academic-presentation-markdown-template-master/presentation/image/16.png) 


## Результаты

- Мы установили Kali и проверили работу данной ОС.


## Итоговый слайд

- В течение выполнения данной работы нам удалось установить и проверить работу Kali в виртуальной машине.

:::

