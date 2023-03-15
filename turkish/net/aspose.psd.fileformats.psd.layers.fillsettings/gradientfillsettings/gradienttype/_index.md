---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD for .NET API Referansı
description: GradientFillSettings mülk. Degradenin türünü alır veya ayarlar.
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Degradenin türünü alır veya ayarlar.

```csharp
public GradientType GradientType { get; set; }
```

### Mülk değeri

Degradenin türü.

### Örnekler

Aşağıdaki kod, farklı türde degradelerle görüntüleri kaydeder ve Aspose.PSD'nin degradeyi nasıl çizeceğini gösterir.

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

### Ayrıca bakınız

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* toplantı [Aspose.PSD](../../../)


