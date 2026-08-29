---
title: "Klasse ColorFillSettings"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.ColorFillSettings Klasse. Einstellungen für Farbe-Füll-Effekt"
type: docs
weight: 2040
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---
{{< psd/tize >}}
## ColorFillSettings class

Farbfüllungseffekt-Einstellungen

```csharp
public class ColorFillSettings : BaseFillSettings, IColorFillSettings
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ColorFillSettings](colorfillsettings/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/color/) { get; set; } | Liest oder setzt die Farbe. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/filltype/) { get; } | Der Fülltyp |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Strich-Effekt-Ebene mit dem Fülltyp - Farbe.

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

// Testdatei nach Bearbeitung
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

### Siehe auch

* class [BaseFillSettings](../basefillsettings/)
* interface [IColorFillSettings](../icolorfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


