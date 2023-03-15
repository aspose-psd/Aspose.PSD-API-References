---
title: Class VectorImage
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.VectorImage sınıf. Vektör görüntüsü tüm vektör görüntü türleri için temel sınıftır.
type: docs
weight: 5720
url: /tr/net/aspose.psd/vectorimage/
---
## VectorImage class

Vektör görüntüsü, tüm vektör görüntü türleri için temel sınıftır.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Paletin otomatik olarak ayarlanıp ayarlanmadığını gösteren bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | Şunu alır:[`Image`](../image/) konteyner. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | dosya formatı değerini alır |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değer alır veya ayarlar. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Görüntü yüksekliğini alır. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Nesne yüksekliğini inç olarak alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesme monitörünü alır veya ayarlar. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Nesne boyutunu inç cinsinden alır. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temelden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleri tarafından temsil edilen belirtilen dosya biçiminde kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına göre seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmeden tutmak için yardımcı olabilir. Örneğin, piksel başına 1 bit olacak şekilde siyah-beyaz bir PNG görüntüsü yüklersek ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save/) yöntemiyle, piksel başına 8 bitlik çıktı PNG görüntüsü üretilir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, karşılık gelen kaydetme seçeneklerini almak için bu yöntemi kullanın ve onları öğesini[`Save`](../image/save/)ikinci parametre olarak yöntem. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini alttaki akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Ayrıca bakınız

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


