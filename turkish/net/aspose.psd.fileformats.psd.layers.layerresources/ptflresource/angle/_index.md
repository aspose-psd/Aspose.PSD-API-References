---
title: "PtFlResource.Angle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PtFlResource özelliği. Açıyı alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/
---
{{< psd/tize >}}
## PtFlResource.Angle property

Açıyı alır veya ayarlar.

```csharp
public double Angle { get; set; }
```

### Property Value

Açı.

## Örnekler

Aşağıdaki kod, PtFlResource içinde Angle özelliğinin desteğini gösterir.

```csharp
[C#]

string sourceFile = "PatternFillLayerWide_0.psd";
string outputFile = "PatternFillLayerWide_0_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    FillLayer fillLayer = (FillLayer)image.Layers[1];
    PatternFillSettings fillSettings = (PatternFillSettings)fillLayer.FillSettings;
    fillSettings.Angle = 70;
    fillLayer.Update();
    image.Save(outputFile, new PsdOptions());
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    FillLayer fillLayer = (FillLayer)image.Layers[1];
    PatternFillSettings fillSettings = (PatternFillSettings)fillLayer.FillSettings;

    Assert.AreEqual(70, fillSettings.Angle);
}
```

### Ayrıca Bakınız

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


