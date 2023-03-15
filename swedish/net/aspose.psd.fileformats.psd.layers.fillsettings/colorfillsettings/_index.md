---
title: Class ColorFillSettings
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.ColorFillSettings klass. Färgfyllningseffektinställningar
type: docs
weight: 1930
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---
## ColorFillSettings class

Färgfyllningseffektinställningar

```csharp
public class ColorFillSettings : BaseFillSettings, IColorFillSettings
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/color/) { get; set; } | Hämtar eller ställer in färgen. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/filltype/) { get; } | Fyllningstypen |

### Exempel

Följande kod visar stöd för linjeeffektlagret med fyllningstyp - Färg.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

var sourceFileName = "Stroke.psd";
var exportPath = "StrokeColorChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, colorStroke.BlendMode);
    AssertAreEqual((byte)255, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);

    fillSettings.Color = Color.Yellow;

    colorStroke.Opacity = 127;
    colorStroke.BlendMode = BlendMode.Color;
    im.Save(exportPath);
}

// Testfil efter redigering
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, colorStroke.BlendMode);
    AssertAreEqual((byte)127, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Yellow, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);
}
```

### Se även

* class [BaseFillSettings](../basefillsettings/)
* interface [IColorFillSettings](../icolorfillsettings/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* hopsättning [Aspose.PSD](../../)


