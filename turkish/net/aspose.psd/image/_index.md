---
title: "Image sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Image sınıfı. Görüntü, tüm görüntü türleri için temel sınıftır."
type: docs
weight: 5090
url: /tr/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Görüntü, tüm görüntü türleri için temel sınıftır.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan renginin değerini alır veya ayarlar. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Görüntünün piksel başına bit sayısını alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntünün sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | `Image` konteynerini alır. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Dosya formatının değerini alır |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Resmin yüksekliğini alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekmediğini gösteren bir değeri alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Görüntü genişliğini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Belirtilen akıştan yeni bir görüntü yükler. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Belirtilen dosyadan yeni bir görüntü yükler. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Belirtilen akıştan yeni bir görüntü yükler. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Belirtilen dosyadan yeni bir görüntü yükler. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağından emin olur. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit/piksel siyah-beyaz PNG görüntüsü yüklerseniz ve ardından [`Save`](../datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olacaktır. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [`Save`](./save/) yöntemine geçirin. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/#save)() | Görüntü verilerini temel akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Görüntünün belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen *loadOptions* kullanılarak yüklenip yüklenemeyeceğini belirler. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Dosya biçimini alır. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Dosya biçimini alır. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Geçerli görüntüyü sığdıran dikdörtgeni alır. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Geçerli görüntüyü sığdıran dikdörtgeni alır. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Orantılı bir yüksekliği alır. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Orantılı bir genişliği alır. |

## Örnekler

Bu örnek, PsdOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumunu belirten Source özelliği.

```csharp
[C#]

//PsdOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource bir örneği oluşturun ve bunu PsdOptions örneği için Source olarak atayın.
//İkinci Boolean parametre, oluşturulacak dosyanın geçici (IsTemporal) olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image bir örneği oluşturun ve Create metodunu çağırarak PsdOptions örneğiyle başlatın.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca Bakınız

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


