---
title: "Sınıf PsdImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.PsdImage sınıfı. PSD dosyalarını yükleme, düzenleme, kaydetme yeteneği sağlayan ve ayrıca özellikleri güncelleme, filigran ekleme, grafik işlemleri gerçekleştirme veya bir dosya formatını diğerine dönüştürme imkanı sunan PsdImage sınıfını tanımlar. Aspose.PSD, katman olarak içe aktarmayı ve aşağıdaki formatlara dışa aktarmayı destekler: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb ve ayrıca seçilebilir metinle Pdf dışa aktarmayı."
type: docs
weight: 4080
url: /tr/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

PsdImage sınıfını tanımlar; bu sınıf PSD dosyalarını yükleme, düzenleme, kaydetme, özellikleri güncelleme, filigran ekleme, grafik işlemleri gerçekleştirme veya bir dosya formatını başka birine dönüştürme yeteneği sağlar. Aspose.PSD, katman olarak içe aktarmayı ve aşağıdaki formatlara dışa aktarmayı destekler: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb ve seçilebilir metin içeren Pdf dışa aktarımı.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Mevcut raster görüntüden (psd görüntüsü değil) RGB renk modu, 4 kanal, 8 bit/kanal ve sıkıştırma olmadan `PsdImage` sınıfının yeni bir örneğini başlatır. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Belirtilen yoldan raster görüntüden (akışta psd görüntüsü değil) `PsdImage` sınıfının yeni bir örneğini başlatır. PSD görüntüsünü varsayılan parametrelerle başlatmak için kullanılır - Renk modu - rgb, 4 kanal, 8 bit/kanal, Sıkıştırma - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Belirtilen yoldan raster görüntüden (yolda psd görüntüsü değil) `PsdImage` sınıfının yeni bir örneğini başlatır. PSD görüntüsünü varsayılan parametrelerle başlatmak için kullanılır - Renk modu - rgb, 4 kanal, 8 bit/kanal, Sıkıştırma - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Belirtilen genişlik ve yükseklik ile `PsdImage` sınıfının yeni bir örneğini başlatır. Boş bir psd görüntüsü oluşturmak için kullanılır. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Mevcut raster görüntüden (psd görüntüsü değil) yapıcı parametreleriyle `PsdImage` sınıfının yeni bir örneğini başlatır. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Belirtilen yoldan raster görüntüden (akışta psd görüntüsü değil) yapıcı parametreleriyle `PsdImage` sınıfının yeni bir örneğini başlatır. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Belirtilen yoldan raster görüntüden (yolda psd görüntüsü değil) yapıcı parametreleriyle `PsdImage` sınıfının yeni bir örneğini başlatır. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ile belirtilen sıkıştırma modu parametreleriyle `PsdImage` sınıfının yeni bir örneğini başlatır. Boş bir psd görüntüsü oluşturmak için kullanılır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Etkin katmanı alır veya ayarlar. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan renginin değerini alır veya ayarlar. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Kanal başına bit sayısını alır. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Görüntünün piksel başına bit sayısını alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntünün sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD kanal sayısını alır. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. Doğru renk dönüşümü için RgbColorProfile ile eşleşmelidir. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Renk modunu alır veya ayarlar. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Sıkıştırma yöntemini alır. |
| [Container](../../aspose.psd/image/container/) { get; } | `[`Image`](../../aspose.psd/image/)` kapsayıcısını alır. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Dosya formatının değerini alır |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Global açıyı alır veya ayarlar. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Genel katman maskesi bilgilerini alır. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Genel katman kaynaklarını alır veya ayarlar. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Gri tonlamalı (monochrome) PSD görüntüleri için GRAY renk profilini alır veya ayarlar. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Bu [`RasterImage`](../../aspose.psd/rasterimage/) nesnesinin inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisi içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Resmin şeffaf renge sahip olup olmadığını gösteren bir değeri alır. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Resmin yüksekliğini alır. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Bu `PsdImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Bu resmin opaklığını alır. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD görüntü kaynaklarını alır veya ayarlar. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Resim verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | PSD görüntüsünün düzleştirilip düzleştirilmediğini gösteren bir değeri alır. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ham veri yüklemesinin kullanılabilir olup olmadığını gösteren bir değeri alır. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD katmanlarını alır veya ayarlar. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Bağlantılı katman yöneticisini alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Resim bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Dizinli renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ham satır boyutunu bayt cinsinden alır. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. Doğru renk dönüşümü için CmykColorProfile ile eşleşmeli. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Akıllı nesne sağlayıcısını alır. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Bu `PsdImage`'in [`Timeline`](./timeline/) öğesini alır. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Görüntünün saydam rengini alır. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını gösteren bir değeri alır veya ayarlar. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Sürümü alır veya ayarlar. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Bu `PsdImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Görüntü genişliğini alır. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Siyah beyaz ayar katmanını ekler. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Parlaklık/kontrast ayar katmanını ekler. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Varsayılan parametrelerle kanal mikseri ayar katmanını ekler |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Renk dengesi ayar katmanını ekler. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Eğriler Ayar katmanını ekler. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Pozlama ayar katmanını ekler. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | GradientMap Ayar katmanını ekler. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Ton/doygunluk ayar katmanını ekler. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Ters çevirme ayar katmanını ekler. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Katmanı ekler. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Katman grubunu ekler. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Seviye ayar katmanını ekler. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | FotoFiltre katmanını ekler. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Posterize Ayar katmanını ekler. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Yeni bir normal katman ekler. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Seçici renk ayar katmanını ekler. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Boş Şekil katmanı ekle. Yollar olmadan. Kaydetmeden önce şekil katmanına eklenmelidir. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Yeni bir Metin katmanı ekler. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Eşik ayar katmanını ekler. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Canlılık ayar katmanını ekler. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Görüntünün parlaklığını ayarlar. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Görüntü kontrastı |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Bu görüntü formatını seçeneklerde belirtilen formata dönüştürür. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Görüntüyü kırpma. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Kaydırmalarla görüntüyü kırp. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Mevcut görüntüde dithering uygular. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Mevcut görüntüde dithering uygular. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Tüm katmanları düzleştirir. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için yararlı olabilir. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsünü yükleyip [`Save`](../../aspose.psd/datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [`Save`](../../aspose.psd/image/save/) yöntemine geçirin. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Bir görüntü pikselini alır. Performans Uyarısı: Tüm görüntü pikselleri üzerinde döngü yapmak için bu yöntemi kullanmaktan kaçının, çünkü önemli performans sorunlarına yol açabilir. Daha verimli piksel manipülasyonu için tüm piksel dizisini aynı anda almak amacıyla `LoadArgb32Pixels` yöntemini kullanın. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Eğim açısını alır. Bu yöntem, taranan metin belgelerinde tarama sırasında eğim açısını belirlemek için uygulanabilir. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-bit ARGB piksellerini yükler. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-bit ARGB piksellerini yükler. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK formatında pikselleri yükler. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK formatında pikselleri yükler. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili olan [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) yöntemini kullanın. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Pikselleri paketler halinde kısmen yükler. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Pikselleri yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Katmanları birleştirir. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Açıyı normalleştirir. Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) ve [`Rotate`](../../aspose.psd/rasterimage/rotate/) yöntemlerini kullanır. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) ve [`Rotate`](../../aspose.psd/rasterimage/rotate/) yöntemlerini kullanır. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Görüntüyü merkezin etrafında döndür. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Görüntüyü merkezin etrafında döndür. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini temel akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32 bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Pikselleri kaydeder. Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) yöntemini kullanın. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Bu `PsdImage` için çözünürlüğü ayarlar. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Varsayılan PSD sürümü. |

## Örnekler

Aşağıdaki kod, görüntüyü belirli bir açı değeriyle döndürme yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Tüm görüntünün döndürülmesi
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Katmanın döndürülmesi
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Ayrıca Bakınız

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


