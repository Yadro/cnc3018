---
description: первая настройка
---

# FlatCAM

## Вкладка Options

## Gerber Options

**Plot Options** - настройки отображения

* Plot отвечает за отображение
* Sold за закраску
* Multicolored за разноцветность слоев

### **Isolations Routing**

Настройка фрезеровки дорожек

**Isolations Routing** - настройка выреза дорожек

* **Tool dia** - диаметр инструмента (обычно 0,1-0,2мм)
* **Width (#passes)** - количество проходов
* **Pass Overlap** - перекрытие проходов. Указывается в частях от ширины. 0.15 это 15% от ширины инструмента.
* **Combine Passes** — эта галочка сливает разные проходы в одну обработку. Если галка снята, то два прохода дадут два файла.

**Board Cutout - обрезка платы**

* **Tool Dia -** диаметр инструмента
* **Margin** - отступ от края
* **Gap size** - ширина крепежных язычков
* **Gaps - расположение язычков**
  * **2(T/B)** — два вверху и внизу
  * **2(L/R)** — два слева и справа
  * **4** - по всем сторонам

**Non-copper regions - \<TODO>**

### **Exellon Options**

* **Plot Options** - отображение сверловок
  * Plot
  * Solid
* Create CNC Job
  * Cut Z - глубина сверловки (0.09мм оптимально)
  * Travel Z
  * Feed rate
  * Toolchange Z
  * Spindle speed
* Mill Holes

****

