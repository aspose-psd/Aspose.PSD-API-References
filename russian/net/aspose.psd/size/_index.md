---
title: Struct Size
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Size структура. Представляет размер.
type: docs
weight: 5550
url: /ru/net/aspose.psd/size/
---
## Size structure

Представляет размер.

```csharp
public struct Size
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Size](size/#constructor)(Point) | Инициализирует новый экземпляр`Size` структура из указанного[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | Инициализирует новый экземпляр`Size` структура из указанных размеров. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Получает новый экземпляр`Size` структура, которая имеет[`Width`](./width/) и[`Height`](./height/) значения равны нулю. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Получает или задает вертикальный компонент этого`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Получает значение, указывающее, является ли это`Size` имеет ширину и высоту 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Получает или задает горизонтальную составляющую этого`Size` . |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Добавляет ширину и высоту одного`Size` структура по ширине и высоте другой`Size`структура. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Преобразует указанный[`SizeF`](../sizef/) структура к`Size` структуры путем округления значений`Size` структура к следующему более высокому целочисленному значению. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Преобразует указанный[`SizeF`](../sizef/) структура к`Size` структуры путем округления значений[`SizeF`](../sizef/) структура до ближайших целочисленных значений. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Вычитает ширину и высоту из одного`Size` структура от ширины и высоты другой`Size`структура. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Преобразует указанный[`SizeF`](../sizef/) структура к`Size` структуру путем усечения значений[`SizeF`](../sizef/) структура до следующего меньшего целочисленного значения. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Проверяет, является ли указанный объект`Size` с такими же размерами как этот`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Возвращает хеш-код для этого`Size`структура. |
| override [ToString](../../aspose.psd/size/tostring/)() | Создает удобочитаемую строку, представляющую этот`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | Добавляет ширину и высоту одного`Size` структура по ширине и высоте другой`Size`структура. |
| [operator ==](../../aspose.psd/size/op_equality/) | Проверяет, являются ли два`Size` структуры равны. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Преобразует указанный`Size` к[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Преобразует указанный`Size` к[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | Проверяет, являются ли два`Size` структуры разные. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Вычитает ширину и высоту из одного`Size` структура от ширины и высоты другой`Size`структура. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


