---
title: Struct RectangleF
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.RectangleF структура. Хранит набор из четырех чисел с плавающей запятой которые представляют положение и размер прямоугольника.
type: docs
weight: 5350
url: /ru/net/aspose.psd/rectanglef/
---
## RectangleF structure

Хранит набор из четырех чисел с плавающей запятой, которые представляют положение и размер прямоугольника.

```csharp
public struct RectangleF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Инициализирует новый экземпляр`RectangleF` структура с указанным расположением и размером. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Инициализирует новый экземпляр`RectangleF` структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Получает новый экземпляр`RectangleF` структура, которая имеет[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) и[`Height`](./height/) значения равны нулю. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y/) и[`Height`](./height/) этого`RectangleF`структура. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Получает или задает высоту этого`RectangleF`структура. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Получает значение, указывающее,[`Width`](./width/) или[`Height`](./height/) свойство этого`RectangleF` имеет нулевое значение. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Получает или задает x-координату левого края этого`RectangleF`структура. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Получает или задает координаты левого верхнего угла этого`RectangleF`структура. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x/) и[`Width`](./width/) этого`RectangleF`структура. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Получает или задает размер этого`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Получает или задает координату y верхнего края этого`RectangleF`структура. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Получает или задает ширину этого`RectangleF`структура. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Получает или задает x-координату левого верхнего угла этого`RectangleF`структура. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Получает или задает координату Y верхнего левого угла этого`RectangleF`структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Создает`RectangleF` структура с левым верхним и правым нижним углами в указанных местах. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Создает новый[`Rectangle`](../rectangle/) из двух указанных точек. Две вершины созданного[`Rectangle`](../rectangle/) будет равно переданному*point1* и*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Создает и возвращает увеличенную копию указанного`RectangleF`состав. Копия завышена на указанную сумму. Исходный прямоугольник остается без изменений. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Возвращает`RectangleF` структура, представляющая собой пересечение двух прямоугольников. Если пересечения нет и пусто`RectangleF` возвращается. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Создает наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Определяет, содержится ли указанная точка в этом`RectangleF`структура. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом`RectangleF`структура. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Определяет, содержится ли указанная точка в этом`RectangleF`структура. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Проверяет,*obj* это`RectangleF` с таким же расположением и размером этого`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Получает хэш-код для этого`RectangleF`структура. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | раздувает это`RectangleF`на указанную сумму. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | раздувает это`RectangleF` структуру на указанную сумму. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Заменяет это`RectangleF`структура с пересечением себя и заданного`RectangleF`структура. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Преобразует атрибуты этого`RectangleF` в удобочитаемую строку. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Реализует оператор /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Проверяет, являются ли два`RectangleF` структуры имеют одинаковое расположение и размер. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Преобразует указанный[`Rectangle`](../rectangle/) структура к`RectangleF`структура. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Проверяет, являются ли два`RectangleF` структуры отличаются расположением или размером. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Реализует оператор *. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


