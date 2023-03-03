---
title: Struct Point
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Point структура. Представляет упорядоченную пару целых чисел x и yкоординат определяющую точку на двумерной плоскости.
type: docs
weight: 5260
url: /ru/net/aspose.psd/point/
---
## Point structure

Представляет упорядоченную пару целых чисел x- и y-координат, определяющую точку на двумерной плоскости.

```csharp
public struct Point
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Point](point/#constructor_1)(int) | Инициализирует новый экземпляр`Point` структура с использованием координат, заданных целочисленным значением. |
| [Point](point/#constructor)(Size) | Инициализирует новый экземпляр`Point` структура из[`Size`](../size/)структура. |
| [Point](point/#constructor_2)(int, int) | Инициализирует новый экземпляр`Point` структура с указанными координатами. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Получает новый экземпляр`Point` структура, которая имеет[`X`](./x/) и[`Y`](./y/) значения равны нулю. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Получает значение, указывающее, является ли это`Point` пуст. |
| [X](../../aspose.psd/point/x/) { get; set; } | Получает или задает координату x этого`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Получает или задает координату y этого`Point` . |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Добавляет указанный[`Size`](../size/) к указанному`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Преобразует указанный[`PointF`](../pointf/) к`Point` путем округления значений[`PointF`](../pointf/) к следующему большему целочисленному значению. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Преобразует указанный[`PointF`](../pointf/) к`Point` объект, округляя`Point` значения до ближайшего целого числа. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Возвращает результат вычитания указанного[`Size`](../size/) из указанного`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Преобразует указанный[`PointF`](../pointf/) к`Point` путем усечения значений`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Указывает, является ли это`Point` содержит те же координаты, что и указанныйObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Возвращает хеш-код для этого`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Переводит это`Point` указанным`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Переводит это`Point`на указанную сумму. |
| override [ToString](../../aspose.psd/point/tostring/)() | Преобразует это`Point` в удобочитаемую строку. |
| [operator +](../../aspose.psd/point/op_addition/) | Переводит`Point` заданным[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Сравнивает два`Point` объекты. Результат указывает, являются ли значения[`X`](./x/) и[`Y`](./y/) свойства двух`Point` объекты равны. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Преобразует указанный`Point` структура к[`Size`](../size/)структура. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Преобразует указанный`Point` структура к[`PointF`](../pointf/)структура. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Сравнивает два`Point` объекты. Результат указывает, являются ли значения[`X`](./x/) или[`Y`](./y/) свойства двух`Point` объекты не равны. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Переводит`Point` отрицанием данного[`Size`](../size/) . |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


