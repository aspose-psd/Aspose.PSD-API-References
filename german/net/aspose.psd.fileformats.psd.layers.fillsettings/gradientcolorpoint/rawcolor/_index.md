---
title: "GradientColorPoint.RawColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GradientColorPoint-Eigenschaft. Ruft die Farbe des Rohwerts ab oder legt sie fest"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/rawcolor/
---
{{< psd/tize >}}
## GradientColorPoint.RawColor property

Liest oder setzt die Farbe des Rohwerts.

```csharp
public RawColor RawColor { get; set; }
```

### Property Value

Die Farbe des Rohwerts.

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

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


