---
title: Class CurvResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource sınıf. Sınıf CurvResource. Eğrilerin Kaynağı Ayarlama Layer 1 bayt  eğriler kullanılıyorsa 0 map üzerinde piksel kullanılıyorsa 1 0 ise 2 bayt  kısa. Varsayılan 1 4 bayt  int. Yalnızca son bayt bit kullanılır. İlk bit 1 kanal içindir Dördüncü bit 4 kanal için example 2 bayt  kısa noktalar count 4 bayt  nokta sayısı  eğri noktaları 2 kısa ilk konum ikinci yükseklik 4 bayt  Crv  2 bayt  Curves 4 bayt  int için kısa varsayılan değer 4tür. Varsayılan 1 4 bayt  nokta sayısı 4 bayt  nokta sayısı  eğri 2nin noktaları kısa birinci konum ikinci yükseklik 04 bayt  1 ise four için satır başı 2 bayt  kısa. Varsayılan 1 4 bayt  int. Yalnızca son bayt kullanılır. Bir kanal bir bittir. İlk bit 1 kanal içindir Dördüncü bit 4 kanal içindir example 256  değiştirilen kanalların sayısı  0  255 aralığındaki kanalın sıralı değerleri 4 bayt  kelime Crv  2 bayt  kısa. map üzerindeki pikseller için varsayılan 3tür 4 bayt  int Kanal sayısı 2  256 bayt  kanal dizini için kısa 2 256 0  255 aralığındaki kanalın sıralı değerleridir
type: docs
weight: 2400
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Sınıf CurvResource. Eğrilerin Kaynağı Ayarlama Layer 1 bayt - eğriler kullanılıyorsa 0, map üzerinde piksel kullanılıyorsa 1, 0 ise: 2 bayt - kısa. Varsayılan 1 4 bayt - int. Yalnızca son bayt bit kullanılır. İlk bit 1 kanal içindir, Dördüncü bit 4 kanal için example 2 bayt - kısa noktalar count 4 bayt * nokta sayısı - eğri noktaları 2 kısa: ilk konum, ikinci yükseklik 4 bayt - "Crv " 2 bayt - Curves 4 bayt - int için kısa varsayılan değer 4'tür. Varsayılan 1 4 bayt - nokta sayısı 4 bayt * nokta sayısı - eğri 2'nin noktaları kısa: birinci konum, ikinci yükseklik 0-4 bayt - 1 ise four için satır başı: 2 bayt - kısa. Varsayılan 1 4 bayt - int. Yalnızca son bayt kullanılır. Bir kanal bir bittir. İlk bit 1 kanal içindir, Dördüncü bit 4 kanal içindir example 256 * değiştirilen kanalların sayısı - 0 - 255 aralığındaki kanalın sıralı değerleri 4 bayt - kelime "Crv " 2 bayt - kısa. map üzerindeki pikseller için varsayılan 3'tür 4 bayt - int Kanal sayısı (2 + 256) bayt - kanal dizini için kısa 2, 256, 0 - 255 aralığındaki kanalın sıralı değerleridir

```csharp
public class CurvResource : AdjustmentLayerResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Yeni bir örneğini başlatır.`CurvResource` sınıf. |
| [CurvResource](curvresource/#constructor_1)(int) | Yeni bir örneğini başlatır.`CurvResource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Bu örneğin ayrı depolanan veri olup olmadığını gösteren bir değer alır veya ayarlar. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | psd sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | İmzayı alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Etkin yöneticiyi alır. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Kanal verilerini alır. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Eğri yöneticisini alır. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


