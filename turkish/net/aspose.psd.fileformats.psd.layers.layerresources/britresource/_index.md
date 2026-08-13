---
title: "BritResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource sınıfı. BritResource sınıfı. Parlaklık/Kontrast Ayar Katmanı kaynağı."
type: docs
weight: 2600
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

BritResource sınıfı. Parlaklık/Kontrast Ayarlama Katmanı'nın kaynağı

```csharp
public class BritResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BritResource](britresource/#constructor)() | Yeni bir `BritResource` sınıfı örneği başlatır. |
| [BritResource](britresource/#constructor_1)(byte[]) | Yeni bir `BritResource` sınıfı örneği başlatır. PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir: 2 Parlaklık 2 Kontrast 2 Parlaklık ve kontrast için ortalama değer 1 Yalnızca Lab rengi Modern PSD'lerde (CS5 ve üzeri) CgEd'in olduğu yerde kullanılmaz. CgEd bilgi özelliklerini depolar. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Yeni bir `BritResource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Parlaklığı alır veya ayarlar. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Kontrastı alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | [lab color] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Parlaklık ve kontrast için ortalama değeri alır veya ayarlar. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


