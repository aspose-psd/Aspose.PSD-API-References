---
title: "Sınıf PhflResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource sınıfı. PhflResource sınıfı. Exposure Adjustment Layer 2 kaynağı. Versiyon 3 veya 2. XYZ rengi için her biri 12 4 bayt. Sadece Versiyon 3'te 10 2 bayt renk uzayı, ardından 4 2 bayt renk bileşeni. Sadece Versiyon 2'de 4 Yoğunluk 1 Parlaklığı Koru."
type: docs
weight: 3240
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Sınıf PhflResource. Exposure Adjustment Layer 2 kaynağı Versiyon ( = 3 ) veya ( = 2 ) 12 4 bayt XYZ renk için (Sadece Versiyon 3) 10 2 bayt renk uzayı ardından 4 * 2 bayt renk bileşeni (Sadece Versiyon 2) 4 Yoğunluk 1 Parlaklığı Koru

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Yoğunluğu alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Parlaklığın korunup korunmadığını gösteren bir değeri alır veya ayarlar [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Sürümü alır. Varsayılan 2 veya 3'tür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB'nin rengini alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB rengini ayarlar. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


