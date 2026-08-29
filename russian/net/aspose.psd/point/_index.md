---
title: "Структура Point"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.Point. Представляет упорядоченную пару целых координат x и y, определяющих точку в двумерной плоскости"
type: docs
weight: 5760
url: /ru/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости.

```csharp
public struct Point
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Point](point/#constructor_1)(int) | Инициализирует новый экземпляр структуры `Point`, используя координаты, заданные целым значением. |
| [Point](point/#constructor)(Size) | Инициализирует новый экземпляр структуры `Point` из структуры [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | Инициализирует новый экземпляр структуры `Point` с указанными координатами. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Получает новый экземпляр структуры `Point`, у которого значения [`X`](./x/) и [`Y`](./y/) установлены в ноль. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Получает значение, указывающее, пустой ли этот `Point`. |
| [X](../../aspose.psd/point/x/) { get; set; } | Получает или задает координату x этого `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Получает или задает координату y этого `Point`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Добавляет указанную [`Size`](../size/) к указанному `Point`. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Преобразует указанный [`PointF`](../pointf/) в `Point`, округляя значения [`PointF`](../pointf/) до следующего большего целого. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Преобразует указанный [`PointF`](../pointf/) в объект `Point`, округляя значения `Point` до ближайшего целого. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Возвращает результат вычитания указанной [`Size`](../size/) из указанного `Point`. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Преобразует указанный [`PointF`](../pointf/) в `Point`, отбрасывая дробную часть значений `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Указывает, содержит ли этот `Point` те же координаты, что и указанный объект. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Возвращает хеш-код для этого `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Смещает этот `Point` на указанный `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Смещает этот `Point` на указанную величину. |
| override [ToString](../../aspose.psd/point/tostring/)() | Преобразует этот `Point` в читаемую человеком строку. |
| [operator +](../../aspose.psd/point/op_addition/) | Смещает `Point` на заданную [`Size`](../size/). |
| [operator ==](../../aspose.psd/point/op_equality/) | Сравнивает два объекта `Point`. Результат указывает, равны ли значения свойств [`X`](./x/) и [`Y`](./y/) у двух объектов `Point`. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Преобразует указанную структуру `Point` в структуру [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Преобразует указанную структуру `Point` в структуру [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | Сравнивает два объекта `Point`. Результат указывает, неравны ли значения свойств [`X`](./x/) или [`Y`](./y/) у двух объектов `Point`. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Перемещает `Point` на отрицательное значение заданного [`Size`](../size/). |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


