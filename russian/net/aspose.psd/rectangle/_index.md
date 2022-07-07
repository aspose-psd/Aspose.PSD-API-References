---
title: Rectangle
second_title: Справочник по Aspose.PSD для .NET API
description: Сохраняет набор из четырех целых чисел представляющих расположение и размер прямоугольника.
type: docs
weight: 5220
url: /ru/net/aspose.psd/rectangle/
---
## Rectangle structure

Сохраняет набор из четырех целых чисел, представляющих расположение и размер прямоугольника.

```csharp
public struct Rectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Инициализирует новый экземпляр структуры[`Rectangle`](../rectangle)с указанным расположением и размером. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр структуры[`Rectangle`](../rectangle)с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | Получает новый экземпляр структуры[`Rectangle`](../rectangle)с[`X`](./x),[`Y`](./y),[`Width`](./width)иHeightравны нулю. |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y)и[`Height`](./height)значения свойств этой[`Rectangle`](../rectangle)структуры. |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | Получает или задает высоту этой[`Rectangle`](../rectangle)структуры. |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | Получает значение, указывающее, имеют ли все числовые свойства этого[`Rectangle`](../rectangle)нулевые значения. |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | Получает или устанавливает x-координату левого края этой[`Rectangle`](../rectangle)структуры. |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | Получает или задает координаты верхнего левого угла этой[`Rectangle`](../rectangle)структуры. |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x)и[`Width`](./width)значения свойств этой[`Rectangle`](../rectangle)структуры. |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | Получает или устанавливает размер этого[`Rectangle`](../rectangle). |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | Получает или задает координату y верхнего края этой[`Rectangle`](../rectangle)структуры. |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | Получает или задает ширину этой[`Rectangle`](../rectangle)структуры. |
| [X](../../aspose.psd/rectangle/x) { get; set; } | Получает или задает координату x левого верхнего угла этой[`Rectangle`](../rectangle)структуры. |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | Получает или задает координату y верхнего левого угла этой[`Rectangle`](../rectangle)структуры. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | Преобразует указанную структуру[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)структура путем округления значений[`RectangleF`](../rectanglef)до следующего большего целочисленного значения. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | Создает структуру[`Rectangle`](../rectangle)с указанными местоположениями ребер. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | Создает новый[`Rectangle`](../rectangle)из двух указанных точек. Две вертикали созданного[`Rectangle`](../rectangle)будут равны переданным*point1*и*point2*. Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанной[`Rectangle`](../rectangle)структуры. Копия завышена на указанную сумму. Исходная структура[`Rectangle`](../rectangle)остается неизменной. |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | Возвращает третью структуру[`Rectangle`](../rectangle), представляющую пересечение двух других[`Rectangle`](../rectangle)структуры. Если пересечения нет, возвращается пустой[`Rectangle`](../rectangle). |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)путем округления значений[`RectangleF`](../rectanglef)до ближайших целых значений. |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)путем усечения значений[`RectangleF`](../rectanglef). |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | Получает структуру[`Rectangle`](../rectangle), содержащую объединение двухПрямоугольникструктуры. |
| [Contains](../../aspose.psd/rectangle/contains#contains)(Point) | Определяет, содержится ли указанная точка в этой[`Rectangle`](../rectangle)структуре. |
| [Contains](../../aspose.psd/rectangle/contains#contains_1)(Rectangle) | Определяет, содержится ли прямоугольная область, представленная*rect*полностью внутри этого[`Rectangle`](../rectangle)структура. |
| [Contains](../../aspose.psd/rectangle/contains#contains_2)(int, int) | Определяет, содержится ли указанная точка в этой[`Rectangle`](../rectangle)структуре. |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | Проверяет, является ли*obj*структурой[`Rectangle`](../rectangle)с тем же расположением и размером этой структуры[`Rectangle`](../rectangle). |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | Возвращает хэш-код для этой[`Rectangle`](../rectangle)структуры. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate)(Size) | Увеличивает этот[`Rectangle`](../rectangle)на указанную величину. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate_1)(int, int) | Увеличивает этот[`Rectangle`](../rectangle)на указанную величину. |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | Заменяет этот[`Rectangle`](../rectangle)на пересечение себя и указанногоПрямоугольник. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | Определяет, пересекается ли этот прямоугольник с*rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.psd/rectangle/offset#offset)(Point) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectangle/offset#offset_1)(int, int) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectangle/tostring)() | Преобразует атрибуты этого[`Rectangle`](../rectangle)в удобочитаемую строку. |
| [operator ==](../../aspose.psd/rectangle/op_equality) | Проверяет, имеют ли две структуры[`Rectangle`](../rectangle)одинаковое расположение и размер. |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | Проверяет, различаются ли две структуры[`Rectangle`](../rectangle)расположением или размером. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
