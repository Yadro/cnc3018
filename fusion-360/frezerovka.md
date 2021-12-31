---
description: Инструкция как создать G-Code программу для фрезеровки
---

# Фрезеровка

* Открываем нужную вам модель во Fusion 360

### Setup

* Переходим в режим **Manufacture** (кликаем по кнопке DESIGN слева от панели инструментов)
* Добавляем **Setup**. Жмём кнопку **Setup** на панели инструментов. Он будет содержать пути фрезеровки детали.
* Заполняем параметры в Setup:

{% tabs %}
{% tab title="" %}
[Ссылка на документацию на англ](https://help.autodesk.com/view/fusion360/ENU/)

Начни с вкладки **Setup**
{% endtab %}

{% tab title="Setup" %}
**1) Machine**

Выбор станка, которым будем фрезеровать

Нажимаем `Select...` и в открывшемся окне жмем на Fusion 360 library и выбираем  `Autodesk Generic 3-axis` (This machine has YXZ on the Head) станок и жмём Download Model для загрузки модели.

**2) Setup**

Operation Type - тип операции, которую будем осуществлять, в нашем случае это фрезеровка

* Milling - Фрезеровка
* Turning or Mill/Turn
* Cutting - Резка
* ​Additive - 3D печать

**3) Work Coordinate System (WCS)**

Здесь мы выбираем точку отсчета от которой будет вестись фрезеровка

* Orientation
* Origin - Выбрать Stock box point
* Stock Point - Удобнее всего выбрать один из верхних углов от Stock box

**4) Model**

Выбираем модель, которую собираемся обрабатывать
{% endtab %}

{% tab title="Stock" %}
//TODO

Переходи в Post Process
{% endtab %}

{% tab title="Part Position" %}
//TODO

Переходи в Post Process
{% endtab %}

{% tab title="Post Process" %}
**1) Program**

Program Name - этим значением будет заполнятся файл фрезеровки, который получим на выходе

**2) Machine WCS**

WCS Offset - по умолчанию "0"
{% endtab %}
{% endtabs %}

### Создаем программу фрезеровки

* Теперь переходим к созданию программы фрезеровки
* Выбираем созданный Setup и жмем 2D Countur

### Создаем g-code



