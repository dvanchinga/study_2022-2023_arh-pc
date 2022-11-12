---
## Front matter
title: "Шаблон отчёта по лабораторной работе 4"
subtitle: "архитектура компьютера"
author: "ВАНЧИНГА ДЭВИД"

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
Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Выполнение лабораторной работы
1. Установка **TeX Live** и **Pandoc и pandoc-crossref**
: На рисунке выше показано, что я установил TeXLive и Pandoc и
pandoc-crossref перед началом лабораторной работы.
![Название рисунка](image/https://sun9-9.userapi.com/impg/FiymaqZMJRBlucNikqhugWoGzakOjqtm9AN_WA/n5ixb4mI35o.jpg?size=604x393&quality=96&sign=6c5a467448816cfa407847d77d338781&type=album{ #fig:001 width=70% }

![Название рисунка](image/https://sun9-25.userapi.com/impg/gyjDfPPawltLl8KasSFw48ThENRAg21pQ_yZwA/9HkPR_pQ328.jpg?size=967x668&quality=96&sign=7e1bf71bffca9d55a50a7eed795e1e4e&type=album{ #fig:001 width=70% }

\2. Перейдите в каталог курса сформированный при выполнении лабораторной работы №3:
cd ~/work/study/2022-2023/"Архитектура компьютера"/arch-pc/
Обновите локальный репозиторий, скачав изменения из удаленного репозитория с помощью команд git pull

![Название рисунка](image/https://sun9-88.userapi.com/impg/PEZH_Qc6R9Tx0ghGzd3rXqPiPoEbXoqSLZjyAw/ToS6qjlFrn4.jpg?size=604x292&quality=96&sign=cfc8bea6f0ef65884f677048c97e431f&type=album{ #fig:001 width=70% }


\3. Перейдите в каталог с шаблоном отчета по лабораторной работе № 4
cd ~/work/study/2022-2023/"Архитектура



\4. Я открыл report.md файл используя свой текстовый редактор, я завершил
отчет с помощью Makefile.
   ![Название рисунка](image/https://sun9-66.userapi.com/impg/OasRyojVxP832s80ZyBDVx0L5LYbltsg5te7zA/EPzDXHKMkVw.jpg?size=396x604&quality=96&sign=b247ec0054bca5fed65ef2fc41b8a43d&type=album{ #fig:001 width=70% }


Я загрузил файлы в Github
![Название рисунка](image/https://sun9-28.userapi.com/impg/vldL72ME6l_QCKmzRg_HFcxSzi9W3ISQliCjpQ/PWDUWlq7neY.jpg?size=604x415&quality=96&sign=4661076b938d6967f876ded403e14067&type=album{ #fig:001 width=70% }


# Выводы
Вывод: В ходе этой лабораторной работы я приобрел практические навыки
работы с Markdown


# Список литературы{.unnumbered}

::: {#refs}
:::
