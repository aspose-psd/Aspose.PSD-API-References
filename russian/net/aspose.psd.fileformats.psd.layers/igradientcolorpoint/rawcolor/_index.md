---
title: "IGradientColorPoint.RawColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство IGradientColorPoint. Получает или задает цвет необработанного"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/rawcolor/
---
{{< psd/tize >}}
## IGradientColorPoint.RawColor property

Получает или задаёт цвет raw.

```csharp
public RawColor RawColor { get; set; }
```

### Property Value

Цвет необработанного.

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

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* interface [IGradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


