---
title: "CurvResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource sınıfı. CurvResource sınıfı. Eğriler Ayar Katmanı kaynağı. 1 bayt  0, eğriler kullanılıyorsa 1, haritada pikseller kullanılıyorsa 0 ise 2 bayt kısa. Varsayılan 1 4 bayt int. Yalnızca son bayt bit ile kullanılır. İlk bit 1 kanal içindir, dördüncü bit 4 kanal içindir örnek olarak 2 bayt kısa nokta sayısı 4 bayt nokta sayısı eğri noktaları 2 kısa ilk konum ikinci yükseklik 4 bayt kelime Crv  2 bayt kısa varsayılan 4 Eğriler için 4 bayt int. Varsayılan 1 4 bayt nokta sayısı 4 bayt nokta sayısı eğri noktaları 2 kısa ilk konum ikinci yükseklik 04 bayt Dört için katlanmalı ise 1 ise 2 bayt kısa. Varsayılan 1 4 bayt int. Yalnızca son bayt kullanılır. Bir kanal bir bittedir. İlk bit 1 kanal, dördüncü bit 4 kanal için örnek olarak 256 değiştirilen kanal sayısı 0‑255 aralığında sıralı kanal değerleri 4 bayt kelime Crv  2 bayt kısa. Varsayılan 3 haritada pikseller için 4 bayt int Kanal sayısı 2  256 bayt kısa 2 kanal indeksi için 256, 0‑255 aralığında sıralı kanal değerleridir."
type: docs
weight: 2660
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

CurvResource sınıfı. Eğriler Ayarlama Katmanı kaynağı 1 byte - eğriler kullanılıyorsa 0, haritada pikseller kullanılıyorsa 1; eğer 0 ise: 2 byte - short. Varsayılan 1 4 byte - int. Sadece son byte bit ile kullanılır. İlk bit 1 kanal için, dördüncü bit 4 kanal için örnek olarak 2 byte - short nokta sayısı 4 byte * nokta sayısı - eğri noktaları 2 short: ilk konum, ikinci yükseklik 4 byte - word "Crv " 2 byte - short varsayılan 4 (Eğriler için) 4 byte - int. Varsayılan 1 4 byte - nokta sayısı 4 byte * nokta sayısı - eğri noktaları 2 short: ilk konum, ikinci yükseklik 0-4 byte - dört için katlanma önderi eğer 1 ise: 2 byte - short. Varsayılan 1 4 byte - int. Sadece son byte kullanılır. Bir kanal bir bitte. İlk bit 1 kanal için, dördüncü bit 4 kanal için örnek 256 * değişen kanal sayısı - 0-255 aralığında kanal değerleri sıralı 4 byte - word "Crv " 2 byte - short. Varsayılan 3 (harita üzerindeki pikseller için) 4 byte - int Kanal sayısı (2 + 256) byte - short 2 kanal indeksi için, 256 0-255 aralığında kanal değerlerinin sıralı halidir.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Yeni bir `CurvResource` sınıfı örneği başlatır. |
| [CurvResource](curvresource/#constructor_1)(int) | Yeni bir `CurvResource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Bu örneğin verisinin ayrı ayrı depolanıp depolanmadığını gösteren bir değeri alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Etkin yöneticiyi alır. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Kanal verisini alır. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Eğri yöneticisini alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


