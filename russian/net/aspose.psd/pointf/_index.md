---
title: "Структура PointF"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.PointF. Представляет упорядоченную пару чисел с плавающей точкой x и y, определяющих точку в двумерной плоскости"
type: docs
weight: 5770
url: /ru/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Представляет упорядоченную пару координат x и y с плавающей точкой, определяющих точку в двумерной плоскости.

```csharp
public struct PointF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PointF](pointf/)(float, float) | Инициализирует новый экземпляр структуры `PointF` с указанными координатами. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Получает новый экземпляр структуры `PointF`, у которой значения [`X`](./x/) и [`Y`](./y/) установлены в ноль. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Получает значение, указывающее, пуст ли этот `PointF`. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Получает или задает координату x этого `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Получает или задает координату y этого `PointF`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Перемещает заданный `PointF` на указанный [`Size`](../size/). |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Перемещает заданный `PointF` на указанный [`SizeF`](../sizef/). |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Перемещает `PointF` на отрицательное значение указанного размера. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Перемещает `PointF` на отрицательное значение указанного размера. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Указывает, содержит ли этот `PointF` те же координаты, что и указанный Object. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Возвращает хеш‑код для этой структуры `PointF`. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Преобразует этот `PointF` в читаемую человеком строку. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Перемещает `PointF` на заданный [`Size`](../size/). (2 оператора) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Сравнивает две структуры `PointF`. Результат указывает, равны ли значения свойств [`X`](./x/) и [`Y`](./y/) у обеих структур `PointF`. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Определяет, не равны ли координаты указанных точек. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Перемещает `PointF` на отрицательное значение заданного [`Size`](../size/). (2 оператора) |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


