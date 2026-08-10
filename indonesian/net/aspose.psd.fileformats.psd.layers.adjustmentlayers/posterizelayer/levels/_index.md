---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PosterizeLayer. Tingkat lapisan Posterize."
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Tingkat lapisan Posterize.

```csharp
public short Levels { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan PosterizeLayer.

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

### Lihat Juga

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


