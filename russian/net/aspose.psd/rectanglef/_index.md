---
title: RectangleF
second_title: Справочник по Aspose.PSD для .NET API
description: Хранит набор из четырех чисел с плавающей запятой которые представляют положение и размер прямоугольника.
type: docs
weight: 5280
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
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Инициализирует новый экземпляр[`RectangleF`](../rectanglef) структура с указанным расположением и размером. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Инициализирует новый экземпляр[`RectangleF`](../rectanglef) структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty) { get; } | Получает новый экземпляр[`RectangleF`](../rectanglef) структура, которая имеет[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) а также[`Height`](./height) значения равны нулю. |
| [Bottom](../../aspose.psd/rectanglef/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y) а также[`Height`](./height) этого[`RectangleF`](../rectanglef)структура. |
| [Height](../../aspose.psd/rectanglef/height) { get; set; } | Получает или задает высоту этого[`RectangleF`](../rectanglef)структура. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty) { get; } | Получает значение, указывающее,[`Width`](./width) или же[`Height`](./height) свойство этого[`RectangleF`](../rectanglef) имеет нулевое значение. |
| [Left](../../aspose.psd/rectanglef/left) { get; set; } | Получает или задает x-координату левого края этого[`RectangleF`](../rectanglef)структура. |
| [Location](../../aspose.psd/rectanglef/location) { get; set; } | Получает или задает координаты левого верхнего угла этого[`RectangleF`](../rectanglef)структура. |
| [Right](../../aspose.psd/rectanglef/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x) а также[`Width`](./width) этого[`RectangleF`](../rectanglef)структура. |
| [Size](../../aspose.psd/rectanglef/size) { get; set; } | Получает или задает размер этого[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.psd/rectanglef/top) { get; set; } | Получает или задает координату y верхнего края этого[`RectangleF`](../rectanglef)структура. |
| [Width](../../aspose.psd/rectanglef/width) { get; set; } | Получает или задает ширину этого[`RectangleF`](../rectanglef)структура. |
| [X](../../aspose.psd/rectanglef/x) { get; set; } | Получает или задает x-координату левого верхнего угла этого[`RectangleF`](../rectanglef)структура. |
| [Y](../../aspose.psd/rectanglef/y) { get; set; } | Получает или задает координату Y верхнего левого угла этого[`RectangleF`](../rectanglef)структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Создает[`RectangleF`](../rectanglef) структура с левым верхним и правым нижним углами в указанных местах. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints)(PointF, PointF) | Создает новый[`Rectangle`](../rectangle) из двух указанных точек. Две вершины созданного[`Rectangle`](../rectangle) будет равно переданному*point1* а также*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectanglef/inflate)(RectangleF, float, float) | Создает и возвращает увеличенную копию указанного[`RectangleF`](../rectanglef) структура. Копия завышена на указанную сумму. Исходный прямоугольник остается без изменений. |
| static [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF, RectangleF) | Возвращает[`RectangleF`](../rectanglef) структура, представляющая собой пересечение двух прямоугольников. Если пересечения нет и пусто[`RectangleF`](../rectanglef) возвращается. |
| static [Union](../../aspose.psd/rectanglef/union)(RectangleF, RectangleF) | Создает наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение. |
| [Contains](../../aspose.psd/rectanglef/contains#contains)(PointF) | Определяет, содержится ли указанная точка в этом[`RectangleF`](../rectanglef)структура. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_1)(RectangleF) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом[`RectangleF`](../rectanglef)структура. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_2)(float, float) | Определяет, содержится ли указанная точка в этом[`RectangleF`](../rectanglef)структура. |
| override [Equals](../../aspose.psd/rectanglef/equals)(object) | Проверяет,*obj* это[`RectangleF`](../rectanglef) с таким же расположением и размером этого[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode)() | Получает хэш-код для этого[`RectangleF`](../rectanglef)структура. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate)(SizeF) | раздувает это[`RectangleF`](../rectanglef) на указанную сумму. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate_1)(float, float) | раздувает это[`RectangleF`](../rectanglef) структуру на указанную сумму. |
| [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF) | Заменяет это[`RectangleF`](../rectanglef) структура с пересечением себя и заданного[`RectangleF`](../rectanglef)структура. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith)(RectangleF) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.psd/rectanglef/offset#offset)(PointF) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectanglef/offset#offset_1)(float, float) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectanglef/tostring)() | Преобразует атрибуты этого[`RectangleF`](../rectanglef) в удобочитаемую строку. |
| [operator /](../../aspose.psd/rectanglef/op_division) | Реализует оператор /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality) | Проверяет, являются ли два[`RectangleF`](../rectanglef) структуры имеют одинаковое расположение и размер. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit) | Преобразует указанный[`Rectangle`](../rectangle) структура к[`RectangleF`](../rectanglef)структура. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality) | Проверяет, являются ли два[`RectangleF`](../rectanglef) структуры отличаются расположением или размером. |
| [operator *](../../aspose.psd/rectanglef/op_multiply) | Реализует оператор *. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
