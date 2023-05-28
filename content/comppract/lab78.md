---
title: "lab78"
weight: 4

task_code: "lab78"
task_title: "Лабораторные работы 7 и 8"
subject: "Компьютерный практикум"
---

## Цель:

Научиться создавать изображения с помощью JavaScript Canvas API и:

1. Создать страницу с логотипом, повёрнутым на 90
   градусов против часовой стрелки, состоящим из:
   инициалов, записанных в стиле написания
   почтового индекса, и кривой Безье под ними.

2. Создать страницу, на которой полученный
   логотип будет использован, как фоновый узор.

## Функция, отвечающая за создание Canvas'а:

![Canvas creation](./lab7-8-screenshots/canvas-creation-function.png)

## Фрагмент кода, отвечающий за:

* создание нового Canvas’а;

* добавления его к body;

* установки цвета линий;

* поворот на 90 градусов.

Для страницы с логотипом.

![code for logo page](./lab7-8-screenshots/canvas-body-color-turn-logo.png)

## Фрагмент кода, отвечающий за:

* создание нового Canvas’а;
* добавления его к body;
* установки цвета линий;
* поворот на 90 градусов. 

Для страницы, на которой логотип – фоновый узор.

![code for background page](./lab7-8-screenshots/canvas-body-color-turn-background.png)

## Фрагмент кода, отвечающий за написание буквы I:

![main.js after Babel](./lab7-8-screenshots/letter-I.png)

## Фрагмент кода, отвечающий за написание буквы D:

![code for D](./lab7-8-screenshots/letter-D.png)

## Фрагмент кода, отвечающий за написание точек около инициалов:

![code for dots](./lab7-8-screenshots/dots.png)

## Фрагмент кода, отвечающий за рисование кривой Безье:

![code for curve](lab7-8-screenshots/curve.png)

## Фрагмент кода, отвечающий за установку логотипа в качестве фонового узора:

![code for background image](./lab7-8-screenshots/background-code.png)

## Результаты:

![Logo](./lab7-8-screenshots/logo.png)

![Background](./lab7-8-screenshots/background.png)

## Вывод:

В ходе выполнения лабораторной работы были получены навыки работы с JavaScript Canvas API, был создан логотип, были созданы две страницы:

* на одной из них был расположен созданный логотип;
* на другой этот логотип использовался, как фоновый узор.

## Использованные ресурсы:

- https://learn.javascript.ru/url
- https://scriptdev.ru/webapi/canvas/todataurl/
- https://msiter.ru/references/html5-canvas/settransform

## Ссылки на репозитории:
{{<buttons_column>}}
    {{<button text="Отчёт о выполнении лабораторных работ 7-8" link="/comppract/Lab7/Labs7-8.pdf">}}
    {{<button text="Лабораторная работа 7А (Поворот логотипа но 90 градусов)" link="/comppract/Lab7/Lab7A1">}}
    {{<button text="Лабораторная работа 7А (Логотип, как фон)" link="/comppract/Lab7/Lab7A2">}}
{{</buttons_column>}}