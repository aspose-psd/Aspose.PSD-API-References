---
title: Class RasterCachedImage
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.RasterCachedImage sınıf. Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder. Bu görüntü gerektiğinde piksel verilerini önbelleğe alır.
type: docs
weight: 5310
url: /tr/net/aspose.psd/rastercachedimage/
---
## RasterCachedImage class

Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder. Bu görüntü, gerektiğinde piksel verilerini önbelleğe alır.

```csharp
public abstract class RasterCachedImage : RasterImage
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
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Bu örneğin alfaya sahip olup olmadığını gösteren bir değer alır. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değer alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Görüntünün şeffaf renge sahip olup olmadığını gösteren bir değer alır. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Görüntü yüksekliğini alır. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Bunun inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar[`RasterImage`](../rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Bu görüntünün opaklığını alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesme monitörünü alır veya ayarlar. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ham veri yüklemenin mümkün olup olmadığını gösteren bir değer alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Görüntü bileşenlerinin önceden çoğaltılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Ham veri formatını alır. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Geçerli ham veri ayarlarını alır. Bu ayarları kullanırken, verilerin dönüştürme olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Palet dizini sınırların dışında olduğunda kullanılacak geri dönüş dizinini alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Dizinlenmiş renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ham satır boyutunu bayt cinsinden alır. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Görüntünün şeffaf rengini alır. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP meta verilerinin güncellenip güncellenmeyeceğini belirten bir değer alır veya ayarlar. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ham veri yükleme mevcut olduğunda ham veri yüklemenin kullanılıp kullanılmayacağını belirten bir değer alır veya ayarlar. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Bunun inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar[`RasterImage`](../rasterimage/) . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Görüntü genişliğini alır. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Görüntü için parlaklık ayarı. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Görüntü kontrastı |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Entegre görüntü eşikleme kullanılarak Bradley'nin uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikili hale getirilmesi |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Entegre görüntü eşikleme kullanılarak Bradley'nin uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikili hale getirilmesi |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Önceden tanımlanmış eşikle bir görüntünün ikili hale getirilmesi |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Bir görüntünün Otsu eşikleme ile ikileştirilmesi |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Verileri önbelleğe alır ve temelden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleri tarafından temsil edilen belirtilen dosya biçiminde kaydedilip kaydedilemeyeceğini belirler. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | Görüntü kırpılıyor. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Resmi kaydırarak kırpın. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 32-bit ARGB piksellik bir resim alır. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Varsayılan 32 bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyiciyi kullanarak varsayılan ham veri dizisini alır. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Kaynak görüntünün son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına göre seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmeden tutmak için yardımcı olabilir. Örneğin, piksel başına 1 bit olacak şekilde siyah-beyaz bir PNG görüntüsü yüklersek ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save/) yöntemiyle, piksel başına 8 bitlik çıktı PNG görüntüsü üretilir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, karşılık gelen kaydetme seçeneklerini almak için bu yöntemi kullanın ve onları öğesini[`Save`](../image/save/)ikinci parametre olarak yöntem. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Bir görüntü pikseli alır. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Eğim açısını alır. Bu yöntem, tarama sırasında eğim açısını belirlemek için taranan metin belgelerine uygulanabilir. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Bir görüntünün gri tonlamalı gösterimine dönüştürülmesi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32 bit ARGB pikselleri yükler. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-bit ARGB pikselleri yükler. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Pikselleri CMYK formatında yükler. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-bit ARGB piksellerini kısmen paketler halinde yükler. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Pikselleri kısmen paketler halinde yükler. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Pikselleri yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Açıyı normalleştirir. Bu yöntem, çarpık taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem,[`GetSkewAngle`](../rasterimage/getskewangle/) Ve[`Rotate`](../rasterimage/rotate/) yöntemler. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Açıyı normalleştirir. Bu yöntem, çarpık taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem,[`GetSkewAngle`](../rasterimage/getskewangle/) Ve[`Rotate`](../rasterimage/rotate/) yöntemler. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Belirtilen tarama satırı indeksine göre tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Belirtilen tarama satırı indeksine göre tüm tarama satırını okur. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Saydam olmayan tüm renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Saydam olmayan tüm renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Görüntüyü merkez etrafında döndürün. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | Görüntüyü merkez etrafında döndürün. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini alttaki akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32-bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Belirtilen konum için bir görüntü 32-bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Tarama satırının tamamını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Tarama satırının tamamını belirtilen tarama satırı dizinine yazar. |

### Örnekler

Aşağıdaki kod, görüntüyü belirli bir dikdörtgenle kırpma yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // psd'yi kaydet
    image.Save(exportPath, new PsdOptions());

    // png'yi kaydet
    image.Save(exportPathPng, new PngOptions());
}
```

### Ayrıca bakınız

* class [RasterImage](../rasterimage/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


