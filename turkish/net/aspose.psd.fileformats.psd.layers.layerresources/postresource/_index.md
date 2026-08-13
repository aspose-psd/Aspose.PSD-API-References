---
title: "PostResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PostResource sınıfı. PostResource sınıfı. Posterize katman ayarları"
type: docs
weight: 3300
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---
{{< psd/tize >}}
## PostResource class

Sınıf PostResource. Posterize katman ayarları.

```csharp
public class PostResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PostResource](postresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Levels](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/) { get; set; } | Posterize katmanının seviyeleri. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


