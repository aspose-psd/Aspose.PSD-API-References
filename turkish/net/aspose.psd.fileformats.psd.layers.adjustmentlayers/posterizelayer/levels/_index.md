---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PosterizeLayer özelliği. Posterize katmanının seviyeleri"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Posterize katmanının seviyeleri.

```csharp
public short Levels { get; set; }
```

## Örnekler

Aşağıdaki kod, PosterizeLayer desteğini gösterir.

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

### Ayrıca Bakınız

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


