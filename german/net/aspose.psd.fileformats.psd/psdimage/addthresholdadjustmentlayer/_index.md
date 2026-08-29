---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Fügt die Schwellenwert-Anpassungsebene hinzu"
type: docs
weight: 480
url: /de/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Fügt die Schwellenwert-Anpassungsebene hinzu.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Rückgabewert

Die erstellte Schwellenwert-Anpassungsebene.

## Beispiele

Der folgende Code demonstriert die Unterstützung der ThresholdLayer-Anpassungsebene.

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

// Abrufen, prüfen und ändern Sie die Threshold-Anpassungsebene aus dem Bild.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Threshold-Anpassungsebene abrufen.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Parameter der Ebenen prüfen.
            AssertAreEqual(level, (short)115);

            // Parameter der Ebenen festlegen.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Fügen Sie die Threshold-Anpassungsebene dem Bild hinzu und setzen Sie sie.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Threshold-Anpassungsebene hinzufügen.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Parameter der Ebenen festlegen.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Siehe auch

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


