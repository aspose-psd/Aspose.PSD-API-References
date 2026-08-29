---
title: "GradientColorPoint.RawColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GradientColorPoint property. Hämtar eller anger färgen på rådata"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/rawcolor/
---
{{< psd/tize >}}
## GradientColorPoint.RawColor property

Hämtar eller anger färgen på råvärdet.

```csharp
public RawColor RawColor { get; set; }
```

### Property Value

Färgen på rådata.

## Exempel

Följande kod demonstrerar stödet för RawColor-klassen istället för den föråldrade Color-strukturen.

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

### Se även

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


