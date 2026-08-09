---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PixelDataFormat-Eigenschaft. Liefert das PixelDataFormat, das für 64 Bit pro Pixel mit je 16 Bit für Alpha, Rot, Grün und Blau definiert ist."
type: docs
weight: 110
url: /de/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

Liefert das [`PixelDataFormat`](../), das für 64 Bit pro Pixel mit je 16 Bit für Alpha, Rot, Grün und Blau definiert ist.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

Das [`PixelDataFormat`](../), das für 64 Bit pro Pixel mit je 16 Bit für Alpha, Rot, Grün und Blau definiert ist.

## Beispiele

Der folgende Code demonstriert die Unterstützung der RawColor-Klasse anstelle der veralteten Color-Struktur.

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

### Siehe auch

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


