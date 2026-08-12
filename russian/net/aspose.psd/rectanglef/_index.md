---
title: "Структура RectangleF"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.RectangleF. Сохраняет набор из четырёх чисел с плавающей точкой, представляющих положение и размер прямоугольника."
type: docs
weight: 5850
url: /ru/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Сохраняет набор из четырёх чисел с плавающей запятой, представляющих положение и размер прямоугольника.

```csharp
public struct RectangleF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Инициализирует новый экземпляр структуры `RectangleF` с указанным расположением и размером. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Инициализирует новый экземпляр структуры `RectangleF` с указанным расположением и размером. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Возвращает новый экземпляр структуры `RectangleF`, у которого значения [`X`](./x/), [`Y`](./y/), [`Width`](./width/) и [`Height`](./height/) установлены в ноль. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Получает или задает координату y, которая является суммой [`Y`](./y/) и [`Height`](./height/) этой структуры `RectangleF`. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Получает или задает высоту этой структуры `RectangleF`. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Возвращает значение, указывающее, имеет ли свойство [`Width`](./width/) или [`Height`](./height/) этой `RectangleF` значение ноль. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Получает или задает координату x левой грани этой структуры `RectangleF`. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Получает или задает координаты верхнего левого угла этой структуры `RectangleF`. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Получает или задает координату x, которая является суммой [`X`](./x/) и [`Width`](./width/) этой структуры `RectangleF`. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Получает или задает размер этой `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Получает или задает координату y верхней грани этой структуры `RectangleF`. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Получает или задает ширину этой структуры `RectangleF`. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Получает или задает координату x верхнего левого угла этой структуры `RectangleF`. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Получает или задает координату y верхнего левого угла этой структуры `RectangleF`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Создает структуру `RectangleF` с верхним левым и нижним правым углом в указанных позициях. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Создает новый [`Rectangle`](../rectangle/) из двух указанных точек. Две вершины созданного [`Rectangle`](../rectangle/) будут равны переданным *point1* и *point2*. Обычно это противоположные вершины. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Создает и возвращает расширенную копию указанной структуры `RectangleF`. Копия расширяется на заданную величину. Исходный прямоугольник остаётся неизменным. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Возвращает структуру `RectangleF`, представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой `RectangleF`. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Создаёт наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Определяет, находится ли указанная точка внутри этой структуры `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Определяет, полностью ли прямоугольная область, представленная *rect*, содержится в этой структуре `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Определяет, находится ли указанная точка внутри этой структуры `RectangleF`. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Проверяет, является ли *obj* объектом `RectangleF` с тем же расположением и размером, что и эта `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Получает хеш‑код этой структуры `RectangleF`. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Расширяет этот `RectangleF` на заданную величину. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Расширяет структуру `RectangleF` на заданную величину. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Заменяет эту структуру `RectangleF` пересечением её самой и указанной структуры `RectangleF`. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Определяет, пересекается ли этот прямоугольник с *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Изменяет расположение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Изменяет расположение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Преобразует атрибуты этого `RectangleF` в читаемую строку. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Реализует оператор /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Проверяет, имеют ли две структуры `RectangleF` одинаковое расположение и размер. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Преобразует указанную структуру [`Rectangle`](../rectangle/) в структуру `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Проверяет, отличаются ли две структуры `RectangleF` по расположению или размеру. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Реализует оператор *. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


