---
title: NoiseGradient.ExpansionCount
second_title: Aspose.PSD for .NET API Reference
description: NoiseGradient property. Gets or sets the Expansion count   2 for Photoshop 6.0
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/
---
{{< psd/tize >}}
## NoiseGradient.ExpansionCount property

Gets or sets the Expansion count ( = 2 for Photoshop 6.0).

```csharp
public short ExpansionCount { get; set; }
```

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
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
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

* class [NoiseGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


