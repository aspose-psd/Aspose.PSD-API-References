---
title: Class MixrResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource sınıf. Sınıf MixrResource. Kanal Karıştırıcı Ayarı Layer Kaynağı
type: docs
weight: 2820
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Sınıf MixrResource. Kanal Karıştırıcı Ayarı Layer Kaynağı

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Yeni bir örneğini başlatır.`MixrResource` class. PSD biçimi belirtimi aşağıdaki açıklamayı içerir: 2 Versiyon ( = 1) 2 Monochrome 20 RGB veya CMYK rengi artı mikser ayarları için sabit. 4 * 2 bayt renkli, 2 bayt sabit. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Yeni bir örneğini başlatır.`MixrResource` class. PSD biçimi belirtimi aşağıdaki açıklamayı içerir: 2 Versiyon ( = 1) 2 Monochrome 20 RGB veya CMYK rengi artı mikser ayarları için sabit. 4 * 2 bayt renkli, 2 bayt sabit. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.`MixrResource` tek renkli. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | psd sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Kanal bilgisi ham verilerini alır |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Kanal bilgilerini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


