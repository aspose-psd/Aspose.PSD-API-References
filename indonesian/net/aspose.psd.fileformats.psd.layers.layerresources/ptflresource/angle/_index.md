---
title: "PtFlResource.Angle"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "PtFlResource property. Mendapatkan atau mengatur sudut"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/
---
{{< psd/tize >}}
## PtFlResource.Angle property

Mendapatkan atau mengatur sudut.

```csharp
public double Angle { get; set; }
```

### Property Value

Sudut.

## Contoh

Kode berikut menunjukkan dukungan properti Angle dalam PtFlResource.

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

### Lihat Juga

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


