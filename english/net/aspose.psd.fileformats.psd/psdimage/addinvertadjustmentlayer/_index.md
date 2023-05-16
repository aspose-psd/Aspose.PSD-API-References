---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds an invert adjustment layer
type: docs
weight: 360
url: /net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Adds an invert adjustment layer.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Return Value

The created invert layer

## Examples

The following code demonstrates support for the InvertAdjustmentLayer and how to add InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### See Also

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assembly [Aspose.PSD](../../../)


