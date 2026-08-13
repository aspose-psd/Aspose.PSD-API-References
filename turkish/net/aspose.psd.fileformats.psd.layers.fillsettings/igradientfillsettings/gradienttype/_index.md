---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IGradientFillSettings özelliği. Degrade tipini alır veya ayarlar"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

Degrade tipini alır veya ayarlar.

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

Gradyanın tipi.

## Örnekler

Aşağıdaki kod, farklı degrade tipleriyle görüntüler kaydeder ve Aspose.PSD'nin degradeyi nasıl çizdiğini gösterir.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca Bakınız

* enum [GradientType](../../gradienttype/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


