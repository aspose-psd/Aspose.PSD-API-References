---
title: "Sınıf MixrResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource sınıfı. MixrResource sınıfı. Kanal Karıştırıcı Ayar Katmanı'nın kaynağı."
type: docs
weight: 3160
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Sınıf MixrResource. Kanal Karıştırıcı Ayar Katmanı kaynağı

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Yeni bir `MixrResource` sınıfının örneğini başlatır. PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir: 2 Versiyon (= 1) 2 Monokrom 20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Yeni bir `MixrResource` sınıfının örneğini başlatır. PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir: 2 Versiyon (= 1) 2 Monokrom 20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Bu `MixrResource`'un monokrom olup olmadığını gösteren bir değeri alır veya ayarlar. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Kanal bilgisi ham verisini alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Kanal bilgisini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


