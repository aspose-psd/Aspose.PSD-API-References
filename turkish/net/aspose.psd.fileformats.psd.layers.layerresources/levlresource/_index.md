---
title: "LevlResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource sınıfı. LevlResource sınıfı. Pozlama Ayar Katmanı kaynağı."
type: docs
weight: 2950
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Sınıf LevlResource. Pozlama Ayarlama Katmanı Kaynağı

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Yeni bir `LevlResource` sınıfı örneği başlatır. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Yeni bir `LevlResource` sınıfı örneği başlatır. GrayScale, Duotone, RGB, CMYK, Lab renk modlarında desteklenir 2 bayt - Versiyon (=2) 29 * 10 bayt - 5 kısa tam sayı içeren seviye kayıtları seti 4 bayt - Lvls başlığı (292 indeksinde başlar) 2 bayt - Versiyon (=3) 2 bayt - Toplam seviye kaydı sayısı 10 * (Toplam Sayı - 29) Lvls kaynağının sıfır sonu da dört için katlanmalıdır |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Sürümü alır. Varsayılan 2'dir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Kanalı alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


