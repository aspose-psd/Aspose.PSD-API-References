---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ThresholdLayer eigenschap. Haalt en stelt het drempelniveau in"
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

Haalt op en stelt het drempelniveau in.

```csharp
public short Level { get; set; }
```

### Property Value

Het niveau.

## Voorbeelden

De volgende code demonstreert de ondersteuning van de ThresholdLayer-aanpassingslaag.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Haal, controleer en wijzig de Threshold-aanpassingslaag van de afbeelding.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Haal Threshold-aanpassingslaag op.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Controleer laagparameters.
            AssertAreEqual(level, (short)115);

            // Stel laagparameters in.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Voeg de Threshold-aanpassingslaag toe en stel deze in op de afbeelding.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Voeg Threshold-aanpassingslaag toe.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Stel laagparameters in.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Zie ook

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


