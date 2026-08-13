---
title: "Sınıf VectorImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.VectorImage sınıfı. Vektör görüntüsü, tüm vektör görüntüsü türleri için temel sınıftır."
type: docs
weight: 6250
url: /tr/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Vektör görüntüsü, tüm vektör görüntü tipleri için temel sınıftır.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan renginin değerini alır veya ayarlar. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Görüntünün piksel başına bit sayısını alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntünün sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../image/) konteynerini alır. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Dosya formatının değerini alır |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Resmin yüksekliğini alır. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Nesnenin yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekmediğini gösteren bir değeri alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Nesnenin boyutunu inç cinsinden alır. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Nesnenin genişliğini inç cinsinden alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağından emin olur. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir. Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından [`Save`](../datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [`Save`](../image/save/) yöntemine geçirin. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini temel akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Ayrıca Bakınız

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


