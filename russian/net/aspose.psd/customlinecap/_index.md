---
title: "Класс CustomLineCap"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.CustomLineCap. Инкапсулирует пользовательскую определённую линию‑концовку"
type: docs
weight: 710
url: /ru/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

Инкапсулирует пользовательскую определяемую форму конца линии.

```csharp
public class CustomLineCap
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | Инициализирует новый экземпляр класса `CustomLineCap` с указанными контуром и заливкой. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | Инициализирует новый экземпляр класса `CustomLineCap` из указанного существующего перечисления [`LineCap`](../linecap/) с указанными контуром и заливкой. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | Инициализирует новый экземпляр класса `CustomLineCap` из указанного существующего перечисления [`LineCap`](../linecap/) с указанными контуром, заливкой и отступом. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | Получает или задаёт перечисление [`LineCap`](../linecap/), на котором основан этот `CustomLineCap`. |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | Получает или задаёт расстояние между наконечником и линией. |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | Получает или задаёт объект, определяющий заливку для пользовательского наконечника. |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | Получает или задаёт перечисление [`LineJoin`](../linejoin/), определяющее, как соединяются линии, составляющие объект `CustomLineCap`. |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | Получает или задаёт объект, определяющий контур пользовательского наконечника. |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Получает или задаёт величину, на которую следует масштабировать объект `CustomLineCap` класса относительно ширины объекта Pen. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | Получает наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник. |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | Задаёт наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


