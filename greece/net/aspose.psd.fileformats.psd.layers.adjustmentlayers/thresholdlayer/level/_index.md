---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ThresholdLayer ιδιότητα. Λαμβάνει και ορίζει το επίπεδο κατωφλίου"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

Λαμβάνει και ορίζει το επίπεδο κατωφλίου.

```csharp
public short Level { get; set; }
```

### Property Value

Το επίπεδο.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του επιπέδου προσαρμογής ThresholdLayer.

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

// Αποκτήστε, ελέγξτε και αλλάξτε το επίπεδο προσαρμογής Threshold από την εικόνα.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Αποκτήστε το επίπεδο προσαρμογής Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Ελέγξτε τις παραμέτρους των στρωμάτων.
            AssertAreEqual(level, (short)115);

            // Ορίστε τις παραμέτρους των στρωμάτων.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Προσθέστε και ορίστε το επίπεδο προσαρμογής Threshold στην εικόνα.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Προσθέστε το επίπεδο προσαρμογής Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Ορίστε τις παραμέτρους των στρωμάτων.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Δείτε επίσης

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


