---
title: "Структура Size"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Структура Aspose.PSD.Size. Представляет размер."
type: docs
weight: 6050
url: /ru/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Представляет размер.

```csharp
public struct Size
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Size](size/#constructor)(Point) | Инициализирует новый экземпляр структуры `Size` из указанного [`Point`](../point/). |
| [Size](size/#constructor_1)(int, int) | Инициализирует новый экземпляр структуры `Size` из указанных размеров. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Получает новый экземпляр структуры `Size`, у которого значения [`Width`](./width/) и [`Height`](./height/) установлены в ноль. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Получает или задает вертикальный компонент этого `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Получает значение, указывающее, имеет ли этот `Size` ширину и высоту, равные 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Получает или задает горизонтальный компонент этого `Size`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Добавляет ширину и высоту одной структуры `Size` к ширине и высоте другой структуры `Size`. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Преобразует указанную структуру [`SizeF`](../sizef/) в структуру `Size`, округляя её значения до следующего большего целого. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Преобразует указанную структуру [`SizeF`](../sizef/) в структуру `Size`, округляя значения структуры [`SizeF`](../sizef/) до ближайшего целого. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Вычитает ширину и высоту одной структуры `Size` из ширины и высоты другой структуры `Size`. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Преобразует указанную структуру [`SizeF`](../sizef/) в структуру `Size`, отбрасывая дробную часть значений структуры [`SizeF`](../sizef/) до следующего меньшего целого. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Проверяет, является ли указанный объект `Size` с теми же размерами, что и этот `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Возвращает хеш-код для этой структуры `Size`. |
| override [ToString](../../aspose.psd/size/tostring/)() | Создаёт человекочитаемую строку, представляющую этот `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | Добавляет ширину и высоту одной структуры `Size` к ширине и высоте другой структуры `Size`. |
| [operator ==](../../aspose.psd/size/op_equality/) | Проверяет, равны ли две структуры `Size`. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Преобразует указанный `Size` в [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Преобразует указанный `Size` в [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Проверяет, различаются ли две структуры `Size`. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Вычитает ширину и высоту одной структуры `Size` из ширины и высоты другой структуры `Size`. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


