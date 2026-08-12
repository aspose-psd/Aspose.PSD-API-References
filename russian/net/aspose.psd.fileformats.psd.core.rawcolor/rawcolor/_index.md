---
title: "Класс RawColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. Класс Raw Color помогает хранить цвета с любым количеством каналов, любым режимом цвета и любой глубиной цвета. Обратите внимание, что некоторые внутренние классы могут иметь проблемы при преобразовании RawColor в его родной формат, поэтому если API предоставляет вам CMYK‑цвет, надёжнее использовать предоставленный формат. Также могут быть случаи, когда Raw Color может быть преобразован."
type: docs
weight: 1650
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class помогает хранить цвета с любым количеством каналов, любым режимом цвета и любой разрядностью. Обратите внимание, что некоторые внутренние классы могут иметь проблемы с преобразованием RawColor в его родной формат, поэтому, если API предоставляет вам CMYK‑цвет, надежнее использовать предоставленный формат. Также могут быть случаи, когда Raw Color можно преобразовать.

```csharp
public sealed class RawColor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Инициализирует новый экземпляр класса `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Инициализирует новый экземпляр класса `RawColor` из формата пиксельных данных, используя предопределённые режимы цвета |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Режим для последующего цвета. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Получает компоненты цвета. Каждый компонент — отдельный канал, и если вы используете непопулярную цветовую схему, лучше работать с каждым каналом отдельно. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Получает цвет как int, если это возможно. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Получает цвет как long, если это возможно. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Получает битовую глубину Raw Color. Например, для цвета ARGB с 8 битами на канал/компонент глубина составляет 32 бита, а полная глубина ARGB с 16 битами на канал/компонент — 64 бита. Битовая глубина складывается из суммы глубин каналов. Это возможно, если разные каналы имеют разную битовую глубину. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Получает название режима цвета. Название режима цвета формируется из названий каналов/компонентов. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Получите хеш‑код текущего объекта. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Реализует оператор ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Реализует оператор !=. |

## Примеры

Следующий код демонстрирует поддержку класса RawColor вместо устаревшей структуры Color.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


