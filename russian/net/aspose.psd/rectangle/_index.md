---
title: "Структура Rectangle"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.Rectangle. Содержит набор из четырёх целых чисел, представляющих положение и размер прямоугольника"
type: docs
weight: 5840
url: /ru/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Хранит набор из четырёх целых чисел, представляющих положение и размер прямоугольника.

```csharp
public struct Rectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Инициализирует новый экземпляр структуры `Rectangle` с указанным положением и размером. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр структуры `Rectangle` с указанным положением и размером. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Получает новый экземпляр структуры `Rectangle`, у которой значения [`X`](./x/), [`Y`](./y/), [`Width`](./width/) и [`Height`](./height/) установлены в ноль. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Получает или задает координату y, являющуюся суммой значений свойств [`Y`](./y/) и [`Height`](./height/) этой структуры `Rectangle`. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Получает или задает высоту этой структуры `Rectangle`. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Получает значение, указывающее, имеют ли все числовые свойства этой `Rectangle` значение ноль. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Получает или задает координату x левой грани этой структуры `Rectangle`. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Получает или задает координаты верхнего левого угла этой структуры `Rectangle`. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Получает или задает координату x, являющуюся суммой значений свойств [`X`](./x/) и [`Width`](./width/) этой структуры `Rectangle`. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Получает или задает размер этой `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Получает или задает координату y верхней грани этой структуры `Rectangle`. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Получает или задает ширину этой структуры `Rectangle`. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Получает или задает координату x верхнего левого угла этой структуры `Rectangle`. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Получает или задает координату y верхнего левого угла этой структуры `Rectangle`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Преобразует указанную структуру [`RectangleF`](../rectanglef/) в структуру `Rectangle`, округляя значения [`RectangleF`](../rectanglef/) до следующего большего целого числа. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Создает структуру `Rectangle` с указанными позициями граней. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Создает новый `Rectangle` из двух указанных точек. Две вертикали созданного `Rectangle` будут равны переданным *point1* и *point2*. Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанной структуры `Rectangle`. Копия увеличивается на заданную величину. Исходная структура `Rectangle` остается неизменной. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Возвращает третью структуру `Rectangle`, представляющую пересечение двух других структур `Rectangle`. Если пересечения нет, возвращается пустой `Rectangle`. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Преобразует указанную [`RectangleF`](../rectanglef/) в `Rectangle`, округляя её значения до ближайшего целого числа. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Преобразует указанную [`RectangleF`](../rectanglef/) в `Rectangle`, отбрасывая дробную часть значений [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Получает структуру `Rectangle`, содержащую объединение двух структур `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Определяет, находится ли указанная точка внутри этой структуры `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Определяет, полностью ли прямоугольный регион, представленный *rect*, содержится в этой структуре `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Определяет, находится ли указанная точка внутри этой структуры `Rectangle`. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Проверяет, является ли *obj* структурой `Rectangle` с тем же расположением и размером, что и эта структура `Rectangle`. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Возвращает хеш‑код этой структуры `Rectangle`. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Увеличивает эту `Rectangle` на указанную величину. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Увеличивает эту `Rectangle` на указанную величину. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Заменяет эту `Rectangle` пересечением её с указанной `Rectangle`. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Определяет, пересекается ли этот прямоугольник с *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Изменяет расположение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Изменяет расположение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Преобразует атрибуты этой `Rectangle` в читаемую человеком строку. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Проверяет, имеют ли две структуры `Rectangle` одинаковое расположение и размер. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Проверяет, отличаются ли две структуры `Rectangle` расположением или размером. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


