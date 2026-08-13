---
title: "Sınıf RasterImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.RasterImage sınıfı. Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder"
type: docs
weight: 5850
url: /tr/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
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
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Bu örneğin alfa içerip içermediğini gösteren bir değeri alır. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Resmin şeffaf renge sahip olup olmadığını gösteren bir değeri alır. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Resmin yüksekliğini alır. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Bu resmin opaklığını alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekmediğini gösteren bir değeri alır. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ham veri yüklemesinin kullanılabilir olup olmadığını gösteren bir değeri alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Resim bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Dizinli renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ham satır boyutunu bayt cinsinden alır. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Görüntünün saydam rengini alır. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını gösteren bir değeri alır veya ayarlar. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Görüntü genişliğini alır. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Görüntünün parlaklığını ayarlar. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Görüntü kontrastı |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağından emin olur. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Belirtilen dikdörtgeni kırpar. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Kaydırmalarla görüntüyü kırp. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Mevcut görüntüde dithering uygular. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Mevcut görüntüde dithering uygular. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir. Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından [`Save`](../datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [`Save`](../image/save/) yöntemine geçirin. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Bir görüntü pikselini alır. Performans Uyarısı: Tüm görüntü pikselleri üzerinde döngü yapmak için bu yöntemi kullanmaktan kaçının, çünkü önemli performans sorunlarına yol açabilir. Daha verimli piksel manipülasyonu için tüm piksel dizisini aynı anda almak amacıyla `LoadArgb32Pixels` yöntemini kullanın. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Eğim açısını alır. Bu yöntem, taranan metin belgelerinde tarama sırasında eğim açısını belirlemek için uygulanabilir. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-bit ARGB piksellerini yükler. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-bit ARGB piksellerini yükler. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK formatında pikselleri yükler. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK formatında pikselleri yükler. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [`LoadCmyk32Pixels`](./loadcmyk32pixels/) yöntemini kullanın. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Pikselleri paketler halinde kısmen yükler. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Pikselleri yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Açıyı normalleştirir. Bu yöntem, eğik taramayı gidermek için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](./getskewangle/) ve [`Rotate`](./rotate/) yöntemlerini kullanır. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğik taramayı gidermek için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](./getskewangle/) ve [`Rotate`](./rotate/) yöntemlerini kullanır. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü genişletilmiş seçeneklerle yeniden boyutlandırır. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Görüntüyü merkezin etrafında döndür. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Görüntüyü merkezin etrafında döndür. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini temel akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32 bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Pikselleri kaydeder. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [`SaveCmyk32Pixels`](./savecmyk32pixels/) yöntemini kullanın. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Bu `RasterImage` için çözünürlüğü ayarlar. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |

## Örnekler

Bu örnek, Pixel bilgilerini Color tipinde bir diziye nasıl yükleneceğini, diziyi nasıl manipüle edeceğini ve tekrar görüntüye nasıl ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için örnek, MemoryStream nesnesi kullanarak yeni bir Image dosyası (PSD formatında) oluşturur.

```csharp
[C#]

//MemoryStream bir örneği oluşturun.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions bir örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image bir örneği oluşturun.
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Görüntünün piksellerini, alanı görüntü sınırı olarak belirterek alın
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarlar
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //İndeksli pikselin rengini sarıya ayarla
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //İndeksli pikselin rengini maviye ayarla
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    //MemoryStream'i dosyaya yaz
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ayrıca Bakınız

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


