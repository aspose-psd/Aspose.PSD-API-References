---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PixelDataFormat. Возвращает значение PixelDataFormat, определённое для 64‑битного пикселя с 16‑битами для каждого из альфа, красного, зелёного и синего каналов."
type: docs
weight: 110
url: /ru/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

Возвращает [`PixelDataFormat`](../), определённый для 64‑битного пикселя с 16‑битами для каждого из альфа, красного, зелёного и синего.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

[`PixelDataFormat`](../), определённый для 64‑битного пикселя с 16‑битами для каждого из альфа, красного, зелёного и синего.

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

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


