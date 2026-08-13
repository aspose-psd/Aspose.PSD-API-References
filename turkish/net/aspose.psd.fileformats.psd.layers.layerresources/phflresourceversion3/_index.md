---
title: "Sınıf PhflResourceVersion3"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 sınıfı. Sınıf PhflResource. Exposure Adjustment Layer 2 kaynağı. Sürüm   3  veya   2  XYZ rengi için her biri 12 4 bayt. Sadece Sürüm 3'te 10 2 bayt renk uzayı, ardından 4  2 bayt renk bileşeni. Sadece Sürüm 2'de 4 Yoğunluk 1 Parlaklığı Koru"
type: docs
weight: 3260
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

Sınıf PhflResource. Exposure Adjustment Layer 2 kaynağı Versiyon ( = 3 ) veya ( = 2 ) 12 4 bayt XYZ renk için (Sadece Versiyon 3) 10 2 bayt renk uzayı ardından 4 * 2 bayt renk bileşeni (Sadece Versiyon 2) 4 Yoğunluk 1 Parlaklığı Koru

```csharp
public class PhflResourceVersion3 : PhflResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | `PhflResourceVersion3` sınıfının yeni bir örneğini başlatır. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | `PhflResourceVersion3` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | Renk uzayını alır. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | X rengini alır veya ayarlar. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Y rengini alır veya ayarlar. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Z rengini alır veya ayarlar. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Yoğunluğu alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Parlaklığın korunup korunmadığını gösteren bir değeri alır veya ayarlar [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | Sürümü alır. Varsayılan 2 veya 3'tür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | Rengi alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | RGB rengini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


