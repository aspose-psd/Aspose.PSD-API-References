---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD for .NET API Reference
description: VibranceLayer property. Gets or sets the vibrance
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Gets or sets the vibrance.

```csharp
public int Vibrance { get; set; }
```

### Property Value

The vibrance.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Vibrance must be in range from -180 to +180 |

## Examples

The following code example demonstrates support of the VibranceLayer layer and the ability to edit this adjustment.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Creating a new VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### See Also

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


