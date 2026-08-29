---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PosterizeLayer. مستويات طبقة Posterize"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

مستويات طبقة Posterize.

```csharp
public short Levels { get; set; }
```

## أمثلة

الكود التالي يوضح دعم PosterizeLayer.

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

### انظر أيضًا

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


