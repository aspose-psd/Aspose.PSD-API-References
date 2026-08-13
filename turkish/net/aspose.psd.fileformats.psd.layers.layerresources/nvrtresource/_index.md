---
title: "Sınıf NvrtResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource sınıfı. NvrtResource sınıfı. Invert Ayar Katmanı kaynağı"
type: docs
weight: 3180
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Sınıf NvrtResource. Ters Çevirme Ayar Katmanı kaynağı.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | `NvrtResource` sınıfının yeni bir örneğini başlatır. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | `NvrtResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, NvrtResource elde etmeyi gösterir.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // NvrtResource desteklenir.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


