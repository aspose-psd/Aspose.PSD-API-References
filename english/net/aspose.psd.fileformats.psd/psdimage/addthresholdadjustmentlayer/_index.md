---
title: PsdImage.AddThresholdAdjustmentLayer
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds the Threshold adjustment layer
type: docs
weight: 460
url: /net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Adds the Threshold adjustment layer.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Return Value

The created Threshold adjustment layer.

## Examples

The following code demonstrates the support of ThresholdLayer adjustment layer.

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

// Get, check, and change the Threshold adjustment layer from the image.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Get Threshold adjustment layer.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Check layers parameters.
            AssertAreEqual(level, (short)115);

            // Set layers parameters.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Add and set the Threshold adjustment layer to the image.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Add Threshold Adjustment layer.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Set layers parameters.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### See Also

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assembly [Aspose.PSD](../../../)


