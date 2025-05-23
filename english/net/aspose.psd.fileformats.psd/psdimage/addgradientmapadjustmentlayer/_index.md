---
title: PsdImage.AddGradientMapAdjustmentLayer
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds GradientMap Adjustment layer
type: docs
weight: 360
url: /net/aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddGradientMapAdjustmentLayer method

Adds GradientMap Adjustment layer.

```csharp
public GradientMapLayer AddGradientMapAdjustmentLayer()
```

### Return Value

GradientMap instance.

## Examples

The following code demonstrates the support of Gradient map layer.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Add Gradient map adjustment layer.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Check saved changes
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    GradientFillSettings gradientSettings = (GradientFillSettings)gradientMapLayer.GradientSettings;

    AssertAreEqual(90.0, gradientSettings.Angle);
    AssertAreEqual((short)4096, gradientSettings.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(true, gradientSettings.AlignWithLayer);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual(GradientType.Linear, gradientSettings.GradientType);
    AssertAreEqual(100, gradientSettings.Scale);
    AssertAreEqual(0.0, gradientSettings.HorizontalOffset);
    AssertAreEqual(0.0, gradientSettings.VerticalOffset);
    AssertAreEqual("Custom", gradientSettings.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### See Also

* class [GradientMapLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


