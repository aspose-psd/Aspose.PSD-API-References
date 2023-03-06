---
title: Class PhflResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource sınıf. Sınıf PhflResource. Pozlama Ayarı Kaynağı Layer 2 Sürüm   3  veya   2  12 XYZ rengi için her biri 4 bayt Yalnızca Sürüm 3te 10 2 bayt renk alanı ve ardından 4  2 bayt renk bileşeni Yalnızca Sürüm 2de 4 Yoğunluk 1 Parlaklığı Koru
type: docs
weight: 2890
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Sınıf PhflResource. Pozlama Ayarı Kaynağı Layer 2 Sürüm ( = 3 ) veya ( = 2 ) 12 XYZ rengi için her biri 4 bayt (Yalnızca Sürüm 3'te) 10 2 bayt renk alanı ve ardından 4 * 2 bayt renk bileşeni (Yalnızca Sürüm 2'de) 4 Yoğunluk 1 Parlaklığı Koru

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Yoğunluğu alır veya ayarlar. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Katman kaynak anahtarını alır. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [Parlaklığı koru]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | psd sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | İmzayı alır. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Sürümü alır. Varsayılan 2 veya 3 |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB'nin rengini alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB rengini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


