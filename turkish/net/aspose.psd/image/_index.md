---
title: Class Image
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Image sınıf. Görüntü tüm görüntü türleri için temel sınıftır.
type: docs
weight: 4590
url: /tr/net/aspose.psd/image/
---
## Image class

Görüntü, tüm görüntü türleri için temel sınıftır.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Paletin otomatik olarak ayarlanıp ayarlanmadığını gösteren bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | Şunu alır:`Image` konteyner. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | dosya formatı değerini alır |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değer alır veya ayarlar. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Görüntü yüksekliğini alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesme monitörünü alır veya ayarlar. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Görüntü genişliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Belirtilen akıştan yeni bir resim yükler. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Belirtilen dosyadan yeni bir resim yükler. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Belirtilen akıştan yeni bir resim yükler. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Belirtilen dosyadan yeni bir resim yükler. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temelden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleri tarafından temsil edilen belirtilen dosya biçiminde kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına göre seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmeden tutmak için yardımcı olabilir. Örneğin, piksel başına 1 bit olacak şekilde siyah-beyaz bir PNG görüntüsü yüklersek ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save/) yöntemiyle, piksel başına 8 bitlik çıktı PNG görüntüsü üretilir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, karşılık gelen kaydetme seçeneklerini almak için bu yöntemi kullanın ve onları öğesini[`Save`](./save/)ikinci parametre olarak yöntem. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve çevirir. |
| [Save](../../aspose.psd/image/save/#save)() | Görüntü verilerini alttaki akışa kaydeder. |
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
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen akıştan yüklenip yüklenemeyeceğini belirler.*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Dosya biçimini alır. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Dosya biçimini alır. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Geçerli görüntüye uyan dikdörtgeni alır. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Geçerli görüntüye uyan dikdörtgeni alır. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Orantılı bir yükseklik elde eder. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Orantılı bir genişlik alır. |

### Örnekler

Bu örnek, PsdOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için çeşitli özellikler ayarlanır. Özellikle bu durumda gerçek disk konumuna atıfta bulunan Source özelliği.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Bir FileCreateSource örneği oluşturun ve bunu PsdOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Bir Image örneği oluşturun ve Create yöntemini çağırarak onu PsdOptions örneğiyle başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca bakınız

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


