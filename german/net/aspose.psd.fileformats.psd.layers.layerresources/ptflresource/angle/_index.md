---
title: "PtFlResource.Angle"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PtFlResource Eigenschaft. Gibt den Winkel zurück oder legt ihn fest"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/
---
{{< psd/tize >}}
## PtFlResource.Angle property

Liest oder setzt den Winkel.

```csharp
public double Angle { get; set; }
```

### Property Value

Der Winkel.

## Beispiele

Der folgende Code demonstriert die Unterstützung der Angle-Eigenschaft in PtFlResource.

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

### Siehe auch

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


