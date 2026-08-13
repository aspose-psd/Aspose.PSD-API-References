---
title: "PostResource.Levels"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PostResource özelliği. Posterize katmanının seviyeleri"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Posterize katmanının seviyeleri.

```csharp
public short Levels { get; set; }
```

### Dönüş Değeri

Seviyeler int değeri

## Örnekler

Aşağıdaki kod, PostResource'ın manipülasyon yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


