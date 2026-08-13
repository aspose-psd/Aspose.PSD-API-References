---
title: "Sınıf ColorFillSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.ColorFillSettings sınıfı. Renk doldurma efekti ayarları"
type: docs
weight: 2040
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---
{{< psd/tize >}}
## ColorFillSettings class

Renk doldurma efekti ayarları

```csharp
public class ColorFillSettings : BaseFillSettings, IColorFillSettings
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ColorFillSettings](colorfillsettings/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/color/) { get; set; } | Rengi alır veya ayarlar. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/filltype/) { get; } | Doldurma türü |

## Örnekler

Aşağıdaki kod, doldurma türü - Renk ile çizgi efekti katmanının desteğini gösterir.

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

// Düzenlemeden sonra test dosyası
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

### Ayrıca Bakınız

* class [BaseFillSettings](../basefillsettings/)
* interface [IColorFillSettings](../icolorfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


