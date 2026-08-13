---
title: "Sınıf PhflResourceVersion2"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 class. PhflResource sınıfı. Exposure Adjustment Layer 2 kaynağı. Versiyon 3 veya 2. Versiyon 3'te XYZ rengi için her biri 12 4 bayt, sadece renk; Versiyon 2'de 10 2 bayt renk uzayı, ardından 4 2 bayt renk bileşeni. 4 Yoğunluk 1 Parlaklığı Koru."
type: docs
weight: 3250
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Sınıf PhflResource. Exposure Adjustment Layer 2 kaynağı Versiyon ( = 3 ) veya ( = 2 ) 12 4 bayt XYZ renk için (Sadece Versiyon 3) 10 2 bayt renk uzayı ardından 4 * 2 bayt renk bileşeni (Sadece Versiyon 2) 4 Yoğunluk 1 Parlaklığı Koru

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | `PhflResourceVersion2` sınıfının yeni bir örneğini başlatır. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | `PhflResourceVersion2` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Renk uzayını alır. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Renk A bileşenini alır veya ayarlar |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | B bileşenini alır veya ayarlar |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Renkin L bileşenini alır veya ayarlar |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Yoğunluğu alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Parlaklığın korunup korunmadığını gösteren bir değeri alır veya ayarlar [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Sürümü alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Rengi alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | RGB rengini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


