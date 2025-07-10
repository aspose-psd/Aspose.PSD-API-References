---
title: Layer.ApplyLayerMask
second_title: Aspose.PSD for .NET API Reference
description: Layer method. Applies the layer mask to layer then deletes the mask
type: docs
weight: 350
url: /net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Applies the layer mask to layer, then deletes the mask.

```csharp
public void ApplyLayerMask()
```

## Examples

The following code demonstrates the feature to apply mask to the layer.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


