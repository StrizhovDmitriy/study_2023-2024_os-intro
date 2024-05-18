---
## Front matter
title: "Отчет о прохождении 2 этапа внешнего курса"
subtitle: Операционные системы
author: Стрижов Дмитрий Павлович

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

Ознакомится с функуционалом ОС Linux.


# Задание

Просмотреть видеокурс и решить тестовые задания

# Решение тестовой части

![Первое задание](image/1.png){#fig:001 width=70%}

Удаленный сервер – это выделенная вычислительная машина, доступ к которой открывается через интернет. При этом он может располагаться не только локально (на территории самой организации), но также на стороне провайдера.
Применение удалённого сервера. Он используется для хранения данных, обработки информации, а также выполнения различных вычислительных задач.

![Второе задание](image/2.png){#fig:002 width=70%}

Только выбраный мной вариант, так как этот ключ является открытым.

![Третье задание](image/3.png){#fig:003 width=70%}

Ключ -r означает, что копируется директория рекурсивно, а значит и то, что в ней копппируется.

![Четвертое задание](image/4.png){#fig:004 width=70%}

Проверяем имеется ли вообще интернет соединение. Затем промеряем, знает ли компьютер вообще о данной програме.

![Пятое задание](image/5.png){#fig:005 width=70%}

FileZilla — простой в использовании бесплатный FTP-клиент, предназначенный для загрузки и скачивания файлов с FTP-серверов. С помощью данного инструмента вы сможете разместить файлы вашего сайта на сервере Timeweb, подключившись по протоколу FTP или SFTP. FileZilla может использоваться в Microsoft Windows, Mac OS X, FreeBSD и Linux.

![Шестое задание](image/6.png){#fig:006 width=70%}



![Седьмое задание](image/7.png){#fig:007 width=70%}



![Восьмое задание](image/8.png){#fig:008 width=70%}



![Девятое задание](image/9.png){#fig:009 width=70%}

-align Do full multiple alignment.

![Десятое задание](image/10.png){#fig:010 width=70%}

Комбинация Сtrl+С - завершает процесс. Комбинация Сtrl+Z - приостанавливает процесс.

![Одинадцатое задание](image/11.png){#fig:011 width=70%}


![Двенадцатое задание](image/12.png){#fig:012 width=70%}

Если сигнал не перехватывается процессом, процесс уничтожается. Следовательно, это используется для изящного завершения процесса. kill -9 это небезопасный способ жестокого уничтожения процесса. Это эквивалентно выдергиванию шнура питания и может привести к повреждению данных.

![Тринадцатое задание](image/13.png){#fig:013 width=70%}

Команда kill не прекращает работу приостановленных програм.

![Четырнадцатое задание](image/14.png){#fig:014 width=70%}

Остановленная програма не загружает процессор. 

![Пятьнадцатое задание](image/15.png){#fig:015 width=70%}

В оперативной памяти приостановленное приложение не перестает хранится, поэтому будет занимать столько места, сколько занимала изначально.

![Шестнадцатое задание](image/16.png){#fig:016 width=70%}



![Семнадцатое задание](image/17.png){#fig:017 width=70%}



![Восемнадцатое задание](image/18.png){#fig:018 width=70%}

echo "306174 reads; of these:
    306174 (100.00%) were unpaired; of these:
        11 (0.00%) aligned 0 times
        305580 (99.81%) aligned exactly 1 time
        583 (0.19%) aligned >1 times
100.00% overall alignment rate" > bowtie.log

![Девятнадцатое задание](image/19.png){#fig:019 width=70%}



![Двадцатое задание](image/20.png){#fig:020 width=70%}

exit завершает работу tmux.

![Двадцать первое задание](image/21.png){#fig:021 width=70%}

Мы заходили на сервер с терминала, который и закрыли, а tmux будет продолжать свою работу на сервере.

![Двадцать второе задание](image/22.png){#fig:022 width=70%}

Ещё будет предупреждение о том, что работа завершится. Запущенный процесс во вкладке, конечно же, при её закрытии, пропадет.

![Двадцать третье задание](image/23.png){#fig:023 width=70%}

Ctrl+b c — создать новое окно;

Ctrl+b w — выбрать окно из списка;

Ctrl+b 0-9 — открыть окно по его номеру;

Ctrl+b , — переименовать текущее окно;

Ctrl+b % — разделить текущую панель по горизонтали;

Ctrl+b " — разделить текущую панель по вертикали;

Ctrl+b стрелка — перейти на панель, находящуюся в стороне, куда указывает стрелка;

Ctrl+b Ctrl+стрелка — изменить размер текущей панели;

Ctrl+b o — перейти на следующую панель;

Ctrl+b ; — переключаться между текущей и предыдущей панелью;

Ctrl+b x — закрыть текущую панель.

![Двадцать четвертое задание](image/24.png){#fig:024 width=70%}


# Выводы

За время прохождения первого этапа внещнего курса я познакомился с ОС Linux и освоил некоторый его функционал.
