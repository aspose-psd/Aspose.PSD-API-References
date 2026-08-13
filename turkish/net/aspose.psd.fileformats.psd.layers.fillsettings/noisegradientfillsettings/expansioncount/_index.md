---
title: "NoiseGradientFillSettings.ExpansionCount"
second_title: "Aspose.PSD for .NET API Referansı"
description: "NoiseGradientFillSettings özelliği. Genişleme sayısını alır veya ayarlar   Photoshop 6.0 için 2"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/expansioncount/
---
{{< psd/tize >}}
## NoiseGradientFillSettings.ExpansionCount property

Genişleme sayısını alır veya ayarlar ( = Photoshop 6.0 için 2).

```csharp
public short ExpansionCount { get; set; }
```

## Örnekler

Aşağıdaki kod Gradient harita katmanı desteğini gösterir.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Gradient harita ayar katmanı ekle.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Kaydedilen değişiklikleri kontrol et
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    GradientFillSettings gradientSettings = (GradientFillSettings)gradientMapLayer.GradientSettings;

    AssertAreEqual(90.0, gradientSettings.Angle);
    AssertAreEqual((short)4096, gradientSettings.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(true, gradientSettings.AlignWithLayer);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual(GradientType.Linear, gradientSettings.GradientType);
    AssertAreEqual(100, gradientSettings.Scale);
    AssertAreEqual(0.0, gradientSettings.HorizontalOffset);
    AssertAreEqual(0.0, gradientSettings.VerticalOffset);
    AssertAreEqual("Custom", gradientSettings.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Ayrıca Bakınız

* class [NoiseGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


