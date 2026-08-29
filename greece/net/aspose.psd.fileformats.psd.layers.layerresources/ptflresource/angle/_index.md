---
title: "PtFlResource.Angle"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PtFlResource. Λαμβάνει ή ορίζει τη γωνία"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/
---
{{< psd/tize >}}
## PtFlResource.Angle property

Λαμβάνει ή ορίζει τη γωνία.

```csharp
public double Angle { get; set; }
```

### Property Value

Η γωνία.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας Angle στην PtFlResource.

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

### Δείτε επίσης

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


