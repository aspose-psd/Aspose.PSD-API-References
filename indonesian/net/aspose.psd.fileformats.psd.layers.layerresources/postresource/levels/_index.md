---
title: "PostResource.Levels"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PostResource. Tingkat lapisan Posterize"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Tingkat lapisan Posterize.

```csharp
public short Levels { get; set; }
```

### Nilai Kembalian

Nilai int Levels

## Contoh

Kode berikut menunjukkan kemampuan manipulasi PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Lihat Juga

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


