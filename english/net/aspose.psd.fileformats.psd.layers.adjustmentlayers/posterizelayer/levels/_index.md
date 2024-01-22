---
title: PosterizeLayer.Levels
second_title: Aspose.PSD for .NET API Reference
description: PosterizeLayer property. Levels of Posterize layer
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Levels of Posterize layer.

```csharp
public short Levels { get; set; }
```

## Examples

The following code demonstrates the support of PosterizeLayer.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    foreach (Layer layer in image.Layers)
    {
        if (layer is PosterizeLayer)
        {
            ((PosterizeLayer)layer).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### See Also

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../posterizelayer/)
* assembly [Aspose.PSD](../../../)


