---
title: "Структура SizeF"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.SizeF. Хранит упорядоченную пару чисел с плавающей точкой, обычно ширину и высоту прямоугольника."
type: docs
weight: 6060
url: /ru/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Сохраняет упорядоченную пару чисел с плавающей запятой, обычно ширину и высоту прямоугольника.

```csharp
public struct SizeF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Инициализирует новый экземпляр структуры `SizeF` из указанного [`PointF`](../pointf/). |
| [SizeF](sizef/#constructor_1)(SizeF) | Инициализирует новый экземпляр структуры `SizeF` из указанного `SizeF`. |
| [SizeF](sizef/#constructor_2)(float, float) | Инициализирует новый экземпляр структуры `SizeF` из указанных размеров. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Получает новый экземпляр структуры `SizeF`, у которого значения [`Width`](./width/) и [`Height`](./height/) установлены в ноль. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Получает или задает вертикальную компоненту этого `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Получает значение, указывающее, имеет ли этот `SizeF` нулевую ширину и высоту. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Получает или задает горизонтальную компоненту этого `SizeF`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Добавляет ширину и высоту одной структуры `SizeF` к ширине и высоте другой структуры `SizeF`. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Вычитает ширину и высоту одной структуры `SizeF` из ширины и высоты другой структуры `SizeF`. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Проверяет, является ли указанный объект `SizeF` с теми же размерами, что и этот `SizeF`. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Возвращает хеш‑код для этой структуры [`Size`](../size/). |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Преобразует `SizeF` в [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Преобразует `SizeF` в структуру [`Size`](../size/) с усечёнными значениями размеров. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Создаёт человекочитаемую строку, представляющую этот `SizeF`. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Добавляет ширину и высоту одной структуры `SizeF` к ширине и высоте другой структуры `SizeF`. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Проверяет, равны ли две структуры `SizeF`. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Преобразует указанный `SizeF` в [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Проверяет, различаются ли две структуры `SizeF`. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Вычитает ширину и высоту одной структуры `SizeF` из ширины и высоты другой структуры `SizeF`. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


