---
title: Struct SizeF
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.SizeF структура. Хранит упорядоченную пару чисел с плавающей запятой обычно ширину и высоту прямоугольника.
type: docs
weight: 5560
url: /ru/net/aspose.psd/sizef/
---
## SizeF structure

Хранит упорядоченную пару чисел с плавающей запятой, обычно ширину и высоту прямоугольника.

```csharp
public struct SizeF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Инициализирует новый экземпляр`SizeF` структура из указанного[`PointF`](../pointf/) . |
| [SizeF](sizef/#constructor_1)(SizeF) | Инициализирует новый экземпляр`SizeF` структура из указанного`SizeF` . |
| [SizeF](sizef/#constructor_2)(float, float) | Инициализирует новый экземпляр`SizeF` структура из указанных размеров. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Получает новый экземпляр`SizeF` структура, которая имеет[`Width`](./width/) и[`Height`](./height/) значения равны нулю. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Получает или задает вертикальный компонент этого`SizeF` . |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Получает значение, указывающее, является ли это`SizeF` имеет нулевую ширину и высоту. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Получает или задает горизонтальную составляющую этого`SizeF` . |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Добавляет ширину и высоту одного`SizeF` структура по ширине и высоте другой`SizeF`структура. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Вычитает ширину и высоту из одного`SizeF` структура от ширины и высоты другой`SizeF`структура. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Проверяет, является ли указанный объект`SizeF` с такими же размерами как этот`SizeF` . |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Возвращает хеш-код для этого[`Size`](../size/)структура. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Преобразует`SizeF` к[`PointF`](../pointf/) . |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Преобразует`SizeF` к[`Size`](../size/) структура с усеченными значениями размера. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Создает удобочитаемую строку, представляющую этот`SizeF` . |
| [operator +](../../aspose.psd/sizef/op_addition/) | Добавляет ширину и высоту одного`SizeF` структура по ширине и высоте другой`SizeF`структура. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Проверяет, являются ли два`SizeF` структуры равны. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Преобразует указанный`SizeF` к[`PointF`](../pointf/) . |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Проверяет, являются ли два`SizeF` структуры разные. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Вычитает ширину и высоту из одного`SizeF` структура от ширины и высоты другой`SizeF`структура. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


