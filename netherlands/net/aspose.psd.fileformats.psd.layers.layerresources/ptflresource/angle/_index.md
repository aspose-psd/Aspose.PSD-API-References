---
title: "PtFlResource.Angle"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "PtFlResource eigenschap. Haalt de hoek op of stelt deze in"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/
---
{{< psd/tize >}}
## PtFlResource.Angle property

Haalt een waarde op of stelt de hoek in.

```csharp
public double Angle { get; set; }
```

### Property Value

De hoek.

## Voorbeelden

De volgende code demonstreert de ondersteuning van de Angle-eigenschap in PtFlResource.

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

### Zie ook

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


