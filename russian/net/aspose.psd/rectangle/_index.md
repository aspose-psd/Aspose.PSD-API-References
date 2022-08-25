---
title: Rectangle
second_title: Справочник по Aspose.PSD для .NET API
description: Хранит набор из четырех целых чисел представляющих расположение и размер прямоугольника.
type: docs
weight: 5270
url: /ru/net/aspose.psd/rectangle/
---
## Rectangle structure

Хранит набор из четырех целых чисел, представляющих расположение и размер прямоугольника.

```csharp
public struct Rectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Инициализирует новый экземпляр[`Rectangle`](../rectangle) структура с указанным расположением и размером. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр[`Rectangle`](../rectangle) структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | Получает новый экземпляр[`Rectangle`](../rectangle) структура, которая имеет[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) а также[`Height`](./height) значения равны нулю. |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y) а также[`Height`](./height) значения свойств этого[`Rectangle`](../rectangle)структура. |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | Получает или задает высоту этого[`Rectangle`](../rectangle)структура. |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | Получает значение, указывающее, все ли числовые свойства этого[`Rectangle`](../rectangle) имеют нулевые значения. |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | Получает или задает x-координату левого края этого[`Rectangle`](../rectangle)структура. |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | Получает или задает координаты левого верхнего угла этого[`Rectangle`](../rectangle)структура. |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x) а также[`Width`](./width) значения свойств этого[`Rectangle`](../rectangle)структура. |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | Получает или задает размер этого[`Rectangle`](../rectangle) . |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | Получает или задает координату y верхнего края этого[`Rectangle`](../rectangle)структура. |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | Получает или задает ширину этого[`Rectangle`](../rectangle)структура. |
| [X](../../aspose.psd/rectangle/x) { get; set; } | Получает или задает x-координату левого верхнего угла этого[`Rectangle`](../rectangle)структура. |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | Получает или задает координату Y верхнего левого угла этого[`Rectangle`](../rectangle)структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) структура к[`Rectangle`](../rectangle) структура путем округления[`RectangleF`](../rectanglef) значения до следующего более высокого целочисленного значения. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | Создает[`Rectangle`](../rectangle) структура с указанными местоположениями ребер. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | Создает новый[`Rectangle`](../rectangle) из двух указанных точек. Две вертикали созданного[`Rectangle`](../rectangle) будет равно переданному*point1* а также*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанного[`Rectangle`](../rectangle) структура. Копия завышена на указанную сумму. Оригинал[`Rectangle`](../rectangle) структура остается неизменной. |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | Возвращает третий[`Rectangle`](../rectangle) структура, которая представляет собой пересечение двух других[`Rectangle`](../rectangle) структуры. Если пересечения нет, то пустой[`Rectangle`](../rectangle) возвращается. |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) к[`Rectangle`](../rectangle) путем округления[`RectangleF`](../rectanglef) значения до ближайших целочисленных значений. |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) к[`Rectangle`](../rectangle) путем усечения[`RectangleF`](../rectanglef) значения. |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | Получает[`Rectangle`](../rectangle) структура, содержащая объединение двух[`Rectangle`](../rectangle) структуры. |
| [Contains](../../aspose.psd/rectangle/contains#contains)(Point) | Определяет, содержится ли указанная точка в этом[`Rectangle`](../rectangle)структура. |
| [Contains](../../aspose.psd/rectangle/contains#contains_1)(Rectangle) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом[`Rectangle`](../rectangle)структура. |
| [Contains](../../aspose.psd/rectangle/contains#contains_2)(int, int) | Определяет, содержится ли указанная точка в этом[`Rectangle`](../rectangle)структура. |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | Проверяет,*obj* это[`Rectangle`](../rectangle) структура с тем же расположением и размером этого[`Rectangle`](../rectangle)структура. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | Возвращает хеш-код для этого[`Rectangle`](../rectangle)структура. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate)(Size) | раздувает это[`Rectangle`](../rectangle) на указанную сумму. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate_1)(int, int) | раздувает это[`Rectangle`](../rectangle) на указанную сумму. |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | Заменяет это[`Rectangle`](../rectangle) с пересечением себя и указанного[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.psd/rectangle/offset#offset)(Point) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectangle/offset#offset_1)(int, int) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectangle/tostring)() | Преобразует атрибуты этого[`Rectangle`](../rectangle) в удобочитаемую строку. |
| [operator ==](../../aspose.psd/rectangle/op_equality) | Проверяет, являются ли два[`Rectangle`](../rectangle) структуры имеют одинаковое расположение и размер. |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | Проверяет, являются ли два[`Rectangle`](../rectangle) структуры отличаются расположением или размером. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
