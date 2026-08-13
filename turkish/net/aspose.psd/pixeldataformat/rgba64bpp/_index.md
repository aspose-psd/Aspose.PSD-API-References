---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PixelDataFormat özelliği. Alfa, kırmızı, yeşil ve mavi için her biri 16 bit olmak üzere piksel başına 64 bit olarak tanımlanan PixelDataFormat'ı alır."
type: docs
weight: 110
url: /tr/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

`[`PixelDataFormat`](../)` piksel başına 64 bit, alfa, kırmızı, yeşil ve mavi için her biri 16 bit olarak tanımlanan sürümünü alır.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

Piksel başına 64 bit, alfa, kırmızı, yeşil ve mavi için her biri 16 bit olarak tanımlanan [`PixelDataFormat`](../).

## Örnekler

Aşağıdaki kod, eski Color yapısı yerine RawColor sınıfının desteğini gösterir.

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

### Ayrıca Bakınız

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


