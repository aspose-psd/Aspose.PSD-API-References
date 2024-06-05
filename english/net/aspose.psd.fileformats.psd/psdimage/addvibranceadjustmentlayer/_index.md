---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds the Vibrance adjustment layer
type: docs
weight: 490
url: /net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Adds the Vibrance adjustment layer.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Return Value

A newly created Vibrance layer.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


