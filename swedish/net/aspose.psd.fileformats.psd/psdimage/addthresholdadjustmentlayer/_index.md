---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage metod. Lägger till tröskeljusteringslagret"
type: docs
weight: 480
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Lägger till Threshold‑justeringslagret.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Returvärde

Det skapade tröskeljusteringslagret.

## Exempel

Följande kod demonstrerar stödet för ThresholdLayer-justeringslagret.

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

// Hämta, kontrollera och ändra Threshold-justeringslagret från bilden.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Hämta Threshold-justeringslagret.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Kontrollera lagrens parametrar.
            AssertAreEqual(level, (short)115);

            // Ställ in lagrens parametrar.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Lägg till och ange Threshold-justeringslagret till bilden.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Lägg till Threshold-justeringslager.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Ställ in lagrens parametrar.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Se även

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


