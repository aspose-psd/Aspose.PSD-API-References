---
title: Struct Rectangle
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Rectangle структура. Хранит набор из четырех целых чисел представляющих расположение и размер прямоугольника.
type: docs
weight: 5340
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
| [Rectangle](rectangle/#constructor)(Point, Size) | Инициализирует новый экземпляр`Rectangle` структура с указанным расположением и размером. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр`Rectangle` структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Получает новый экземпляр`Rectangle` структура, которая имеет[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) и[`Height`](./height/) значения равны нулю. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y/) и[`Height`](./height/) значения свойств этого`Rectangle`структура. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Получает или задает высоту этого`Rectangle`структура. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Получает значение, указывающее, все ли числовые свойства этого`Rectangle` имеют нулевые значения. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Получает или задает x-координату левого края этого`Rectangle`структура. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Получает или задает координаты левого верхнего угла этого`Rectangle`структура. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x/) и[`Width`](./width/) значения свойств этого`Rectangle`структура. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Получает или задает размер этого`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Получает или задает координату y верхнего края этого`Rectangle`структура. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Получает или задает ширину этого`Rectangle`структура. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Получает или задает x-координату левого верхнего угла этого`Rectangle`структура. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Получает или задает координату Y верхнего левого угла этого`Rectangle`структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef/) структура к`Rectangle` структура путем округления[`RectangleF`](../rectanglef/) значения до следующего более высокого целочисленного значения. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Создает`Rectangle` структура с указанными местоположениями ребер. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Создает новый`Rectangle` из двух указанных точек. Две вертикали созданного`Rectangle` будет равно переданному*point1* и*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанного`Rectangle`состав. Копия завышена на указанную сумму. Оригинал`Rectangle` структура остается неизменной. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Возвращает третий`Rectangle` структура, которая представляет собой пересечение двух других`Rectangle` структуры. Если пересечения нет, то пустой`Rectangle` возвращается. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef/) к`Rectangle` путем округления[`RectangleF`](../rectanglef/) значения до ближайших целочисленных значений. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef/) к`Rectangle` путем усечения[`RectangleF`](../rectanglef/) значения. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Получает`Rectangle` структура, содержащая объединение двух`Rectangle` структуры. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Определяет, содержится ли указанная точка в этом`Rectangle`структура. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом`Rectangle`структура. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Определяет, содержится ли указанная точка в этом`Rectangle`структура. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Проверяет,*obj* это`Rectangle`структура с тем же расположением и размером этого`Rectangle`структура. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Возвращает хеш-код для этого`Rectangle`структура. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | раздувает это`Rectangle`на указанную сумму. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | раздувает это`Rectangle`на указанную сумму. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Заменяет это`Rectangle` с пересечением себя и указанного`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Преобразует атрибуты этого`Rectangle` в удобочитаемую строку. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Проверяет, являются ли два`Rectangle` структуры имеют одинаковое расположение и размер. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Проверяет, являются ли два`Rectangle` структуры отличаются расположением или размером. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


