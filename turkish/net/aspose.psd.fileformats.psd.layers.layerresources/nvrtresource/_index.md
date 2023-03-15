---
title: Class NvrtResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource sınıf. Sınıf NvrtResource. Ters Ayarlama Katmanının Kaynağı.
type: docs
weight: 2840
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

Sınıf NvrtResource. Ters Ayarlama Katmanının Kaynağı.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Yeni bir örneğini başlatır.`NvrtResource` sınıf. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Yeni bir örneğini başlatır.`NvrtResource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | PSD sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | İmzayı alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Yazım aracı bilgi anahtarı. |

### Örnekler

Aşağıdaki örnek, NvrtResource'un nasıl alınacağını gösterir.

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
                    // NvrtResource destekleniyor.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Ayrıca bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


