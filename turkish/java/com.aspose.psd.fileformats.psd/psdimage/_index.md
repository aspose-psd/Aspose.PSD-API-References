---
title: "PsdImage"
second_title: "Java için Aspose.PSD API Referansı"
description: "PsdImage sınıfını tanımlar; bu sınıf PSD dosyalarını yükleme, düzenleme, kaydetme yeteneği sağlar ve ayrıca özellikleri güncelleme, filigran ekleme, grafik işlemleri yapma veya bir dosya formatını diğerine dönüştürme işlevi sunar."
type: docs
weight: 14
url: /tr/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

PsdImage sınıfını tanımlar; bu sınıf PSD dosyalarını yükleme, düzenleme, kaydetme yeteneği sağlar ve ayrıca özellikleri güncelleme, filigran ekleme, grafik işlemleri yapma veya bir dosya formatını diğerine dönüştürme işlevi sunar. Aspose.PSD, katman olarak içe aktarmayı ve aşağıdaki formatlara dışa aktarmayı destekler: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb ve seçilebilir metinli Pdf dışa aktarması.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) kullanarak yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) ve yapıcı parametreleri kullanarak yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Belirtilen yoldan raster görüntüsü (akışta psd görüntüsü değil) kullanarak yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Belirtilen yoldan raster görüntüsü (akışta psd görüntüsü değil) ve yapıcı parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Mevcut raster görüntüsünden (psd görüntüsü değil) RGB renk modu, 4 kanal, 8 bit/kanal ve sıkıştırma olmadan yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Mevcut raster görüntüsünden (psd görüntüsü değil) ve yapıcı parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Belirtilen genişlik ve yükseklik ile yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ve belirtilen sıkıştırma modu parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Varsayılan kodlama adı |
| [DefaultVersion](#DefaultVersion) | Varsayılan PSD sürümü. |
| [OnCreate_internalized](#OnCreate-internalized) | Görüntü yüklendiğinde meydana gelir |
| [OnLoad_internalized](#OnLoad-internalized) | Görüntü createFirstSupportedLoader tarafından yüklendiğinde meydana gelir |
| [OnSave_internalized](#OnSave-internalized) | Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Kredi kullanıldığında meydana gelir |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Katmanlara erişimi senkronize etmek için kullanılabilecek nesne. |
| [horizontalResolution](#horizontalResolution) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Siyah beyaz ayar katmanını ekler. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Parlaklık/kontrast ayar katmanını ekler. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Varsayılan parametrelerle kanal mikseri ayar katmanını ekler |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Renk dengesi ayar katmanını ekler. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Eğriler ayar katmanını ekler. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Pozlama ayar katmanını ekler. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | GradientMap ayar katmanını ekler. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Ton/doygunluk ayar katmanını ekler. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Tersine çevirme ayar katmanını ekler. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Katmanı ekler. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Katman grubunu ekler. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Katmanı indekste ekler. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Seviye ayar katmanını ekler. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Fotoğraf filtresi katmanını ekler. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Posterize ayar katmanını ekler. |
| [addRegularLayer()](#addRegularLayer--) | Yeni bir normal katman ekler. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Seçici renk ayar katmanını ekler. |
| [addShapeLayer()](#addShapeLayer--) | Boş Shape katmanı ekle. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Yeni bir Metin katmanı ekler. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Eşik ayar katmanını ekler. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Canlılık ayar katmanını ekler. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını ayarlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Görüntü kontrastı |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Bir görüntünün gama düzeltmesi. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Yeniden boyutlandırma sürecini başlatır. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley'in bütünsel görüntü eşikleme yöntemiyle uyarlamalı eşikleme algoritması kullanarak bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in bütünsel görüntü eşikleme yöntemiyle uyarlamalı eşikleme algoritması kullanarak bir görüntünün ikilileştirilmesi |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel DataStreamSupporter.DataStreamContainer'dan ek veri yüklemesinin yapılmayacağını garanti eder. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen loadOptions kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Bu görüntü formatını seçeneklerde belirtilen formata dönüştürür. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps'ye dönüştürür. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği oluşturur. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Görüntüyü kırpma. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü kaydırmalarla kırp. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Mevcut görüntü üzerinde dithering uygular. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Mevcut görüntü üzerinde dithering uygular. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Görüntüyü kırpma. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Görüntünün boyutunu değiştirir. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgeni filtreler. |
| [flattenImage()](#flattenImage--) | Tüm katmanları düzleştirir. |
| [getActiveLayer()](#getActiveLayer--) | Etkin katmanı alır veya ayarlar. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Otomatik palet ayarlamasının olup olmadığını gösteren bir değer alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Arka plan rengini alır veya ayarlar. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Kanal başına bit sayısını alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getBounds()](#getBounds--) | Görüntünün sınırlarını alır. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır. |
| [getChannelsCount()](#getChannelsCount--) | PSD kanal sayısını alır. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. |
| [getColorMode()](#getColorMode--) | Renk modunu alır veya ayarlar. |
| [getCompression()](#getCompression--) | Sıkıştırma yöntemini alır. |
| [getContainer()](#getContainer--) | Görüntü konteynerini alır. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Geçerli görüntü seçeneklerini alır. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Nesnenin veri akışını alır. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Derinlemesine palet ayarlamasını alır. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Kısmi piksel yükleyicisi kullanarak varsayılan piksel dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Kısmi piksel yükleyicisi kullanarak varsayılan ham veri dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Varsayılan ham veri dizisini alır. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Varsayılan değiştirme yazı tipini alır veya ayarlar. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Dosya formatını alır. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Dosya formatını alır. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Dosya formatını alır. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Biçim‑özel yerlerden paleti alır |
| [getGlobalAngle()](#getGlobalAngle--) | Genel açıyı alır veya ayarlar. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Genel katman maskesi bilgilerini alır. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Genel katman kaynaklarını alır veya ayarlar. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Gri (monokrom) renk profilini Gri tonlamalı PSD görüntüleri için alır veya ayarlar. |
| [getHeight()](#getHeight--) | Görüntü yüksekliğini alır. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin yatay çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar. |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | PSD katmanlarını alır veya ayarlar. |
| [getImageOpacity()](#getImageOpacity--) | Bu görüntünün opaklığını alır. |
| [getImageResources()](#getImageResources--) | PSD görüntü kaynaklarını alır veya ayarlar. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | İç veri dönüştürücüyü alır. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Kesinti izleyicisini alır. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Katmanı ve maskeyi alır. |
| [getLayers()](#getLayers--) | PSD katmanlarını alır veya ayarlar. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Bağlantılı katman yöneticisini alır. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Bellek yöneticisini alır. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Boyanabilir görüntüyü alır. |
| [getPalette()](#getPalette--) | Renk paletini alır. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Bir görüntü pikselini alır. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Özel yazı tipi önbelleğini oluşturur. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Orantılı bir yüksekliği alır. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Orantılı bir genişliği alır. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | PSD başlığını alır veya ayarlar. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Özel renk dönüştürücüyü alır veya ayarlar. |
| [getRawDataFormat()](#getRawDataFormat--) | Ham veri biçimini alır. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | İndeksli renk dönüştürücüyü alır veya ayarlar. |
| [getRawLineSize()](#getRawLineSize--) | Ham satır boyutunu bayt cinsinden alır. |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. |
| [getRotateMode()](#getRotateMode--) | Döndürme modunu alır veya ayarlar. |
| [getSize()](#getSize--) | Görüntü boyutunu alır. |
| [getSkewAngle()](#getSkewAngle--) | Eğim açısını alır. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Akıllı nesne sağlayıcısını alır. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Kaynak görüntünün dosya yolunu, mevcutsa alır. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Senkronizasyon kökünü alır. |
| [getTimeline()](#getTimeline--) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin Zaman Çizelgesini ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) alır. |
| [getTransparentColor()](#getTransparentColor--) | Görüntünün şeffaf rengini alır. |
| [getUpdateXmpData()](#getUpdateXmpData--) | XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Yepyeni bir kaynak bloğu ile güncellenmiş kaynakları alır. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır. |
| [getUseRawData()](#getUseRawData--) | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Kullanılan paleti alır. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Girişim lisansını alır. |
| [getVersion()](#getVersion--) | Sürümü alır veya ayarlar. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin dikey çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar. |
| [getWidth()](#getWidth--) | Görüntü genişliğini alır. |
| [getXmpData()](#getXmpData--) | XMP meta verilerini alır veya ayarlar. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [hasAlpha()](#hasAlpha--) | Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değeri alır. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [hasTransparencyData()](#hasTransparencyData--) | Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisini içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | İlerleme maksimum değerini alır veya ayarlar |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | İlerlemeyi gösterir. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Belirtilen katmanın sonrasına tüm hazırlıklarla katmanı ekler. |
| [isCached()](#isCached--) | Görüntü verisinin şu anda önbelleğe alınıp alınmadığını belirten bir değeri alır. |
| [isFlatten()](#isFlatten--) | PSD görüntüsünün düzleştirilip düzleştirilmediğini gösteren bir değeri alır. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ham veri yüklemesinin mevcut olup olmadığını belirten bir değeri alır. |
| [isUsePalette()](#isUsePalette--) | Görüntü paletinin kullanılıp kullanılmadığını belirten bir değeri alır. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(String filePath)](#load-java.lang.String-) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | 32-bit ARGB piksellerini yükler. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | 64-bit ARGB piksellerini yükler. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | CMYK formatındaki pikselleri yükler. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | CMYK formatındaki pikselleri yükler. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 32-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Pikselleri paketler halinde kısmen yükler. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Pikselleri yükler. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Kısmi işleme mekanizmasını kullanarak ham görüntü verisini yükler. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Ham veriyi yükler. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Katmanları birleştirir. |
| [normalizeAngle()](#normalizeAngle--) | Açıyı normalleştirir. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Açıyı normalleştirir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Bu [Image](../../com.aspose.psd/image) kapsayıcısı ayarlandığında çağırılır. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Genel metin motoru kaynağını kaldırır - Bu yöntem, işlendikten sonra Adobe Photoshop'ta açılamayan bazı metin katmanlı PSD dosyaları için kullanılır (çoğunlukla eksik yazı tiplerine bağlı metin katmanları için). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntünün boyutunu değiştirir. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Katmanı belirtilen ters ölçekle yeniden boyutlandırır |
| [rotate(float angle)](#rotate-float-) | Görüntüyü merkezin etrafında döndür. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Görüntüyü merkezin etrafında döndür. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Görüntü verisini temel akışa kaydeder. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(String filePath)](#save-java.lang.String-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | 32 bit ARGB piksellerini kaydeder. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Pikselleri kaydeder. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Pikselleri kaydeder. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Pikselleri kaydeder. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Ham veriyi kaydeder. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Belirtilen kaydetme seçenekleri ve sınırlarla görüntü verilerini belirtilen akışa kaydeder. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Etkin katmanı alır veya ayarlar. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Otomatik palet ayarlaması olup olmadığını gösteren bir değer ayarlar. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Arka plan rengini alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. |
| [setColorMode(short value)](#setColorMode-short-) | Renk modunu alır veya ayarlar. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Görüntü konteynerini ayarlar. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Veri yükleyiciyi doğrudan ayarlar. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Nesnenin veri akışını ayarlar. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Paleti biçim‑özel yerlerine ayarlar |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Genel açı. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Genel katman kaynaklarını alır veya ayarlar. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Gri tonlamalı (monokrom) PSD görüntüleri için GRAY renk profili. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin yatay çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | PSD görüntü kaynaklarını alır veya ayarlar. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | İç veri dönüştürücüyü ayarlar. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Kesinti izleyiciyi ayarlar. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | PSD katmanlarını alır veya ayarlar. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Bellek yöneticisini ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini ayarlar. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Özel renk dönüştürücüyü alır veya ayarlar. |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar. |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | İndeksli renk dönüştürücüyü alır veya ayarlar. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin çözünürlüğünü ayarlar. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Döndürme modunu alır veya ayarlar. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisini içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Görüntünün şeffaf rengini alır. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Girişim lisansını ayarlar. |
| [setVersion(int value)](#setVersion-int-) | Sürümü alır veya ayarlar. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin dikey çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta verilerini alır veya ayarlar. |
| [toBitmap()](#toBitmap--) | Raster görüntüyü bitmap'e dönüştürür. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Belirtilen yoldan raster görüntü (yolda PSD görüntüsü değil) kullanarak [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfının yeni bir örneğini başlatır. PSD görüntüsünü varsayılan parametrelerle başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak yol. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) ve yapıcı parametreleri kullanarak yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak yol. |
| colorMode | short | Renk modu. |
| channelBitDepth | short | PSD kanal başına bit derinliği. |
| channels | short | PSD kanal sayısı. |
| psdVersion | int | PSD sürümü. |
| compression | short | Kullanılacak sıkıştırma. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Belirtilen yoldan raster görüntü (akışta psd görüntüsü değil) kullanarak yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. Varsayılan parametrelerle psd görüntüsünü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak akış. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Belirtilen yoldan raster görüntüsü (akışta psd görüntüsü değil) ve yapıcı parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak akış. |
| colorMode | short | Renk modu. |
| channelBitDepth | short | PSD kanal başına bit derinliği. |
| channels | short | PSD kanal sayısı. |
| psdVersion | int | PSD sürümü. |
| compression | short | Kullanılacak sıkıştırma. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Mevcut raster görüntüsünden (psd görüntüsü değil) RGB renk modu, 4 kanal, 8 bit/kanal ve sıkıştırma olmadan yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Mevcut raster görüntüsünden (psd görüntüsü değil) ve yapıcı parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |
| colorMode | short | Renk modu. |
| channelBitDepth | short | PSD kanal başına bit derinliği. |
| channels | short | PSD kanal sayısı. |
| psdVersion | int | PSD sürümü. |
| compression | short | Kullanılacak sıkıştırma. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Belirtilen genişlik ve yükseklik ile yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Görüntü genişliği. |
| height | int | Görüntü yüksekliği. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ile ayrıca belirtilen sıkıştırma modu parametreleriyle yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Görüntü genişliği. |
| height | int | Görüntü yüksekliği. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |
| colorMode | short | Renk modu. |
| channelBitDepth | short | PSD kanal başına bit derinliği. |
| channels | short | PSD kanal sayısı. |
| psdVersion | int | PSD sürümü. |
| compression | short | Kullanılacak sıkıştırma. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Varsayılan kodlama adı

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Varsayılan PSD sürümü.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Görüntü yüklendiğinde meydana gelir

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Görüntü createFirstSupportedLoader tarafından yüklendiğinde meydana gelir

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Kredi kullanıldığında meydana gelir

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Katmanlara erişimi senkronize etmek için kullanılabilecek nesne.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Siyah beyaz ayar katmanını ekler.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Parlaklık/kontrast ayar katmanını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parlaklık | int | Parlaklık. |
| kontrast | int | Kontrast. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Varsayılan parametrelerle kanal mikseri ayar katmanını ekler

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Renk dengesi ayar katmanını ekler.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Eğriler ayar katmanını ekler.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exposure | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Pozlama ayar katmanını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exposure | float | Pozlama. |
| offset | float | Ofset. |
| gammaCorrection | float | Gamma düzeltmesi. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


GradientMap ayar katmanını ekler.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Ton/doygunluk ayar katmanını ekler.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Tersine çevirme ayar katmanını ekler.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Katmanı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Katman. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Katman grubunu ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| groupName | java.lang.String | Grubun adı. |
| indeks | int | Sonra eklenecek katmanın indeksi. |
| startBehaviour | boolean | true olarak ayarlanırsa [start behaviour] grup başlangıçta açık durumda olur, aksi takdirde küçültülmüş durumda olur. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Katmanı indekste ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Katman. |
| indeks | int | İndeks. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Seviye ayar katmanını ekler.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Fotoğraf filtresi katmanını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Renk. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Posterize ayar katmanını ekler.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Yeni bir normal katman ekler.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Seçici renk ayar katmanını ekler.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Boş Shape katmanı ekle. Yollar olmadan. Kaydetmeden önce Shape katmanına eklenmelidir.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Yeni bir Metin katmanı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Katmanın metni. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Katmanın dikdörtgeni. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Eşik ayar katmanını ekler.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Canlılık ayar katmanını ekler.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntünün parlaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parlaklık | int | Parlaklık değeri. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Görüntü kontrastı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kontrast | float | Kontrast değeri ([-100; 100] aralığında) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Bir görüntünün gama düzeltmesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gama | float | Kırmızı, yeşil ve mavi kanallar için gama katsayısı |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Bir görüntünün gama düzeltmesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gamma |
| gammaGreen | float | Yeşil kanal katsayısı için gamma |
| gammaBlue | float | Mavi kanal katsayısı için gamma |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Yeniden boyutlandırma sürecini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni görüntü genişliği. |
| newHeight | int | Yeni görüntü yüksekliği. |

**Returns:**
com.aspose.internal.IResizeController - Yeniden boyutlandırma denetleyicisi.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Bradley'in bütünsel görüntü eşikleme yöntemiyle uyarlamalı eşikleme algoritması kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley'in bütünsel görüntü eşikleme yöntemiyle uyarlamalı eşikleme algoritması kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiği aşarsa, ona 255 değeri atanır, aksi takdirde 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu eşikleme ile bir görüntünün ikilileştirilmesi

### cacheData() {#cacheData--}
```
public void cacheData()
```


Verileri önbelleğe alır ve temel DataStreamSupporter.DataStreamContainer'dan ek veri yüklemesinin yapılmayacağını garanti eder.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Yükleme yapılacak akış. |

**Returns:**
boolean -  true  eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen loadOptions kullanılarak yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Yükleme yapılacak akış. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
boolean -  true  eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |

**Returns:**
boolean -  true  eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
boolean -  true  eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine görüntünün kaydedilip kaydedilemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kullanılacak kaydetme seçenekleri. |

**Returns:**
boolean -  true  eğer görüntü, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilebiliyorsa; aksi takdirde,  false .
### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Bu görüntü formatını seçeneklerde belirtilen formata dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Yeni seçenekler. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


aps'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |
| mode | int | Mod. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Kırpma dikdörtgeni. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS sayfası.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |
| width | int | Genişlik. |
| height | int | Yükseklik. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Görüntüler. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Görüntüler. |
| disposeImages | boolean | eğer  true  olarak ayarlanırsa  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Yeni bir [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) sınıfı örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | PSD başlığı. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Renk verileri. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Görüntü kaynakları. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Katman ve maske bilgisi. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Görüntü verileri. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |
| version | int | PSD sürümü. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |
| noLayerLoad | boolean | Katman yükleme yok |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| width | int |  |
| height | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Görüntüyü kırpma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Bu dikdörtgen. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü kaydırmalarla kırp.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Bu sol kaydırma. |
| rightShift | int | Bu sağ kaydırma. |
| topShift | int | Bu üst kaydırma. |
| bottomShift | int | Bu alt kaydırma. |

### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Mevcut görüntü üzerinde dithering uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Bu titreme yöntemi. |
| bitsCount | int | Titreme için son bit sayısı. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntü üzerinde dithering uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Bu titreme yöntemi. |
| bitsCount | int | Titreme için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Titreme için özel palet. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Görüntüyü kırpma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Bu dikdörtgen. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntünün boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Belirtilen dikdörtgeni filtreler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Bu dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Tüm katmanları düzleştirir.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Etkin katmanı alır veya ayarlar.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Bir görüntünün 32-bit ARGB pikselini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns:**
int - Belirtilen konum için 32-bit ARGB piksel.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Otomatik palet ayarlamasının olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  eğer otomatik palet ayarlaması etkinleştirilirse; aksi takdirde,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengi için bir değeri alır veya ayarlar.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Kanal başına bit sayısını alır.

Değer: Kanal başına bit sayısı.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Görüntünün sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Returns:**
int - tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucu.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


PSD kanal sayısını alır.

Değer: PSD kanal sayısı.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. Doğru renk dönüşümü için RgbColorProfile ile eşleşmelidir.

Değer: CMYK renk profili.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Renk modunu alır veya ayarlar.

Değer: Renk modu.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Sıkıştırma yöntemini alır.

Değer: Sıkıştırma.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Görüntü konteynerini alır.

Değer: Image konteyneri.

Bu özellik null değilse, görüntünün başka bir görüntü içinde bulunduğunu gösterir.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Geçerli görüntü seçeneklerini alır.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Nesnenin veri akışını alır.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Derinlemesine palet ayarlamasını alır.

**Returns:**
boolean - Paleti derinlemesine ayarlar.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Varsayılan 32-bit ARGB piksel dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel alınacak dikdörtgen. |

**Returns:**
int[] - Varsayılan piksel dizisi.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Varsayılan seçenekleri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | java.lang.Object[] | Argümanlar. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Kısmi piksel yükleyicisi kullanarak varsayılan piksel dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel alınacak dikdörtgen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Kısmi piksel yükleyici. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Kısmi piksel yükleyicisi kullanarak varsayılan ham veri dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel alınacak dikdörtgen. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Kısmi ham veri yükleyici. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Ham veri ayarları. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Varsayılan ham veri dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Ham veri alınacak dikdörtgen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Ham veri ayarları. |

**Returns:**
byte[] - Varsayılan ham veri dizisi.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Varsayılan değiştirme yazı tipini alır veya ayarlar. Değiştirme yazı tipi ayarlanırsa, renderleme için kullanılacaktır. Bu yönteme dahili destek için ihtiyacımız var.

**Returns:**
java.lang.String - Değiştirme yazı tipinin adı
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Dosya formatının bir değerini alır

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Dosya formatını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Akış. |

--------------------

Belirlenen dosya formatı, belirtilen görüntünün yüklenebileceği anlamına gelmez. Akışın yüklenip yüklenemeyeceğini belirlemek için CanLoad yöntemi aşırı yüklemelerinden birini kullanın. |

**Returns:**
long - Belirlenen dosya formatı.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Dosya formatını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Akış. |

Belirlenen dosya formatı, belirtilen görüntünün yüklenebileceği anlamına gelmez. Akışın yüklenip yüklenemeyeceğini belirlemek için CanLoad yöntemi aşırı yüklemelerinden birini kullanın. |

**Returns:**
long - Belirlenen dosya formatı.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Dosya formatını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosya yolu. |

Belirlenen dosya formatı, belirtilen görüntünün yüklenebileceği anlamına gelmez. Dosyanın yüklenip yüklenemeyeceğini belirlemek için CanLoad yöntemi aşırı yüklemelerinden birini kullanın. |

**Returns:**
long - Belirlenen dosya formatı.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| width | int | Nesnenin genişliği. |
| height | int | Nesnenin yüksekliği. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| piksel | int[] | 32 bit ARGB pikselleri. |
| width | int | Nesnenin genişliği. |
| height | int | Nesnenin yüksekliği. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Biçim‑özel yerlerden paleti alır

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Genel açıyı alır veya ayarlar.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Genel katman maskesi bilgilerini alır.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Genel katman kaynaklarını alır veya ayarlar.

Değer: Küresel katman kaynakları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Gri (monokrom) renk profilini Gri tonlamalı PSD görüntüleri için alır veya ayarlar.

Değer: GRAY (monokrom) renk profili.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntü yüksekliğini alır.

Değer: Görüntü yüksekliği.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin yatay çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar.

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


PSD katmanlarını alır veya ayarlar.

Değer: PSD katmanları.

--------------------

Katman yoksa, katman ve maske bilgi bölümü içindeki diğer ilgili bilgilerin (katman maskeleri, kaynaklar vb.) korunmayacağını unutmayın.

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Bu görüntünün opaklığını alır.

**Returns:**
float - Opaklık değeri 0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında.
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


PSD görüntü kaynaklarını alır veya ayarlar.

Değer: PSD görüntü kaynakları.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


İç veri dönüştürücüyü alır.

Değer: İç veri dönüştürücü.

**Returns:**
com.aspose.internal.IInnerDataTransformer - iç veri dönüştürücü.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Kesinti izleyicisini alır.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Katmanı ve maskeyi alır.

Değer: Katman ve maske.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


PSD katmanlarını alır veya ayarlar.

Değer: PSD katmanları.

--------------------

Katman yoksa, katman ve maske bilgi bölümü içindeki diğer ilgili bilgilerin (katman maskeleri, kaynaklar vb.) korunmayacağını unutmayın.

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Bağlantılı katman yöneticisini alır.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar.

**Returns:**
int - Kısmi döndürme kaydetme için izin verilen maksimum tahsis.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Bellek yöneticisini alır.

Değer: Bellek yöneticisi.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - bellek yöneticisi.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Kaynak görüntünün en son değiştirildiği tarih ve saati alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useDefault | boolean | true olarak ayarlanırsa, FileInfo'dan gelen bilgileri varsayılan değer olarak kullanır. |

**Returns:**
java.util.Date - Kaynak görüntünün en son değiştirildiği tarih ve saat.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yüklerseniz ve ardından `DataStreamSupporter.Save(string)` yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak `Image.Save(string, ImageOptionsBase)` yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Boyanabilir görüntüyü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Bir görüntü pikselini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer görüntü bileşenleri önceden çarpılmış olmalıysa; aksi takdirde,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Özel yazı tipi önbelleğini oluşturur.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Özel yazı tipi önbelleği.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


İlerleme olayı işleyici bilgilerini alır.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


İlerleme olayı işleyici bilgilerini alır.

Value: İlerleme olayı işleyici bilgisi.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Orantılı bir yüksekliği alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Genişlik. |
| height | int | Yükseklik. |
| newWidth | int | Yeni genişlik. |

**Returns:**
int - Orantılı yükseklik.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Orantılı bir genişliği alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Genişlik. |
| height | int | Yükseklik. |
| newHeight | int | Yeni yükseklik. |

**Returns:**
int - Orantılı genişlik.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


PSD başlığını alır veya ayarlar.

Değer: PSD başlığı.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Özel renk dönüştürücüyü alır veya ayarlar.

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Ham veri biçimini alır.

Değer: Ham veri formatı.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğine dikkat edin.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar.

**Returns:**
int - Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeks
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


İndeksli renk dönüştürücüyü alır veya ayarlar.

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Ham satır boyutunu bayt cinsinden alır.

**Returns:**
int - Bayt cinsinden ham satır boyutu.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. Doğru renk dönüşümü için CmykColorProfile ile eşleşmelidir.

Değer: RGB renk profili.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Döndürme modunu alır veya ayarlar.

**Returns:**
int - Döndürme modu.
### getSize() {#getSize--}
```
public Size getSize()
```


Görüntü boyutunu alır.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Eğim açısını alır. Bu yöntem, taranan metin belgelerinde tarama sırasında eğim açısını belirlemek için uygulanabilir.

**Returns:**
float - Derece cinsinden eğim açısı.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Akıllı nesne sağlayıcısını alır.

Değer: Akıllı nesne sağlayıcı.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Kaynak görüntünün dosya yolunu varsa alır. Kaynak yol bulunamazsa boş bir dize döndürür.

**Returns:**
java.lang.String - Kaynak görüntünün dosya yolu.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Senkronizasyon kökünü alır.

Value: Senkronizasyon kökü.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin Zaman Çizelgesini ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) alır.

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Görüntünün şeffaf rengini alır.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer XMP meta verileri güncelleniyorsa; aksi takdirde,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Yepyeni bir kaynak bloğu ile güncellenmiş kaynakları alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Kaynaklar. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Mevcut kaynaklara eklenecek kaynak. |
| removeDuplicates | boolean | true olarak ayarlanırsa aynı kimliklere sahip kaynakları kaldırır. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Güncellenmiş kaynak blokları içeren bir dizi döndürür.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır.

Value:  true  eğer nesne bellek optimizasyon stratejisi kullanıyorsa; aksi takdirde,  false .

**Returns:**
boolean - nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını gösteren bir değer
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  ham veri yüklemesi mevcut olduğunda ham veri yüklemesi kullanılıyorsa; aksi takdirde,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Kullanılan paleti alır.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Girişim lisansını alır.

**Returns:**
java.lang.Object - Giriş lisansı nesne olarak.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin dikey çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar.

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntü genişliğini alır.

Value: Görüntü genişliği.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP meta verilerini alır veya ayarlar.

Değer: XMP üst verileri.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Bir görüntünün gri tonlamalı temsiline dönüşümü

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar.

Value:  true  eğer bu örnek alfa içeriyorsa; aksi takdirde,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Görüntünün arka plan rengine sahip olup olmadığını belirten bir değeri alır.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar.

Değer: bu örnek görüntüsü değiştiyse true, aksi takdirde false.

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisini içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer: katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalı şeffaflık verisi içeriyorsa true, aksi takdirde false.

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


İlerleme maksimum değerini alır veya ayarlar

Value: İlerleme maksimum değeri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


İlerlemeyi gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Belirtilen katmanın sonrasına tüm hazırlıklarla katmanı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Katman. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Eklenecek katman. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Görüntü verisinin şu anda önbelleğe alınıp alınmadığını belirten bir değeri alır.

**Returns:**
boolean -  true  eğer görüntü verisi önbelleğe alınmışsa; aksi takdirde,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


PSD görüntüsünün düzleştirilip düzleştirilmediğini gösteren bir değeri alır.

Değer: bu örnek düzleştirilmişse true, aksi takdirde false.

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Ham veri yüklemesinin mevcut olup olmadığını belirten bir değeri alır.

**Returns:**
boolean -  true  eğer bu ham veri yüklemesi mevcutsa; aksi takdirde,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Görüntü paletinin kullanılıp kullanılmadığını belirten bir değeri alır.

Value:  true  eğer palet görüntüde kullanılıyorsa; aksi takdirde,  false .

**Returns:**
boolean - görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer.
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntünün yükleneceği akış. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntünün yükleneceği akış. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün yükleneceği dosya. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün yükleneceği dosya. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Görüntünün yükleneceği dosya yolu. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Görüntünün yükleneceği dosya yolu. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


32-bit ARGB piksellerini yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
int[] - Yüklenen 32-bit ARGB piksel dizisi.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


64-bit ARGB piksellerini yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
long[] - Yüklenen 64-bit ARGB piksel dizisi.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


CMYK formatındaki pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
int[] - Yüklenen CMYK pikseller 32-bit tam sayı değerleri olarak sunulur.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


CMYK formatında pikselleri yükler. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili  loadCmyk32Pixels(Rectangle)  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
com.aspose.psd.CmykColor[] - Yüklenen CMYK piksel dizisi.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


32-bit ARGB piksellerini paketler halinde kısmen yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | İstenen dikdörtgen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 32-bit ARGB piksel yükleyicisi. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Pikselleri paketler halinde kısmen yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | İstenen dikdörtgen. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Piksel yükleyicisi. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
com.aspose.psd.Color[] - Yüklenen piksel dizisi.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Kısmi işleme mekanizmasını kullanarak ham görüntü verisini yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Veri yüklenecek görüntünün istenen dikdörtgen alanı. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Ham veri ayarları. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ham veri yükleyicisi. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Ham veriyi yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Ham verinin yükleneceği dikdörtgen. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntünün sınırları. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Yüklenen veri için kullanılacak ham veri ayarları. Belirtilen formatta değilse veri dönüşümü gerçekleştirileceğini unutmayın. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ham veri yükleyicisi. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Görüntünün yükleneceği akış. |
| startPosition | long | Görüntünün yükleneceği başlangıç konumu. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Görüntünün yükleneceği akış. |
| startPosition | long | Görüntünün yükleneceği başlangıç konumu. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Katmanları birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Alt katman. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Üst katman. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Açıyı normalleştirir. Bu yöntem, kaymış taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [.getSkewAngle](../../null/\#getSkewAngle) ve [.rotate(float)](../../null/\#rotate-float-) metodlarını kullanır.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Açıyı normalleştirir. Bu yöntem, kaymış taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [.getSkewAngle](../../null/\#getSkewAngle) ve [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) metodlarını kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeProportionally | boolean | true olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Arka plan rengi. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Bu [Image](../../com.aspose.psd/image) kapsayıcısı ayarlandığında çağırılır.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns:**
int[] - Tarama satırının 32-bit ARGB renk değerleri dizisi.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns:**
com.aspose.psd.Color[] - Tarama satırı piksel renk değerleri dizisi.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Genel metin motoru kaynağını kaldırır - Bu yöntem, işleme sonrasında Adobe Photoshop'ta açılamayan bazı metin katmanlı psd dosyaları için kullanılır (özellikle eksik fontlara sahip metin katmanlarıyla ilgili). Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları izlemelidir: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Değiştirilecek eski renk. |
| oldColorDiff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| newColor | [Color](../../com.aspose.psd/color) | Eski rengi değiştirecek yeni renk. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldColorArgb | int | Değiştirilecek eski renk ARGB değeri. |
| oldColorDiff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| newColorArgb | int | Eski rengi değiştirmek için yeni renk ARGB değeri. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Şeffaf olmayan renkleri değiştirmek için yeni renk. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorArgb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Görüntüyü yeniden boyutlandırır. Varsayılan  ResizeType.LeftTopToLeftTop  kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntünün boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntünün boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırmanın türü. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırmanın türü. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Belirtilen ters ölçekle katmanı yeniden boyutlandırır. (yeni genişlik = eski genişlik / ölçek; yeni yükseklik = eski yükseklik / ölçek)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | double | X ölçeği. |
| scaleY | double | Y ölçeği. |
| resizeType | int | Yeniden boyutlandırmanın türü. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |
| resizeProportionally | boolean | true olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Arka plan rengi. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Görüntü verisini temel akışa kaydeder.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Nesnenin verilerini kaydetmek için akış. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Boş dikdörtgeni, kaynak sınırlarını kullanmak için ayarlayın. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Nesnenin verilerini kaydetmek için akış. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün verilerini kaydetmek için dosya. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün verilerini kaydetmek için dosya. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırları kullanmak için boş dikdörtgen ayarlayın. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |
| overWrite | boolean | true olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Nesnenin verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırları kullanmak için boş dikdörtgen ayarlayın. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


32 bit ARGB piksellerini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| piksel | int[] | 32-bit ARGB piksel dizisi. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Pikselleri kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| piksel | int[] | 32-bit tam sayı değerleri olarak sunulan CMYK pikseller. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Pikselleri kaydeder. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili saveCmyk32Pixels(Rectangle, int[]) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK piksel dizisi. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Pikselleri kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Piksel dizisi. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Ham veriyi kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Ham veri. |
| dataOffset | int | Başlangıç ham veri ofseti. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Ham veri dikdörtgeni. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Verinin içinde olduğu ham veri ayarları. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Belirtilen kaydetme seçenekleri ve sınırlarla, görüntü verilerini belirtilen akıma kaydeder. İsteğe bağlı olarak yalnızca ön izleme render'ı için belirtilen katmanları dışa aktarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kullanılacak kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için  Rectangle.Empty  olarak ayarlayın. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Dışa aktarılacak belirli katmanlar.  null  değeri, tüm katmanlarla varsayılan davranışı gösterir. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Boş dikdörtgeni, kaynak sınırlarını kullanmak için ayarlayın. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Etkin katmanı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| argb32Color | int | Belirtilen konum için 32-bit ARGB piksel. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Otomatik palet ayarlaması olup olmadığını gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true otomatik palet ayarlamasını etkinleştirir; aksi takdirde false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi için bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucu. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. Doğru renk dönüşümü için RgbColorProfile ile eşleşmelidir.

Değer: CMYK renk profili.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Renk modunu alır veya ayarlar.

Değer: Renk modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Görüntü konteynerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Görüntü kapsayıcısı. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Veri yükleyiciyi doğrudan ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Veri yükleyici. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Nesnenin veri akışını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Nesnenin veri akışı. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Paleti biçim‑özel yerlerine ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Yeni 32-bit ARGB paleti. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Genel açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Genel katman kaynaklarını alır veya ayarlar.

Değer: Küresel katman kaynakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Gri tonlamalı (monokrom) PSD görüntüleri için GRAY renk profili.

Değer: GRAY (monokrom) renk profili.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin yatay çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer [kaydetmeden sonra yoksay]; aksi takdirde,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer bu örnek görüntüyü değiştirmişse; aksi takdirde,  false . |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


PSD görüntü kaynaklarını alır veya ayarlar.

Değer: PSD görüntü kaynakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


İç veri dönüştürücüyü ayarlar.

Değer: İç veri dönüştürücü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.IInnerDataTransformer | iç veri dönüştürücü. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Kesinti izleyiciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | kesinti izleyicisi. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


PSD katmanlarını alır veya ayarlar.

Değer: PSD katmanları.

--------------------

Katman yoksa, katman ve maske bilgi bölümü içindeki diğer ilgili bilgilerin (katman maskeleri, kaynaklar vb.) korunmayacağını unutmayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Kısmi döndürme kaydı için izin verilen maksimum tahsis. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Bellek yöneticisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Bellek yöneticisi. |
| needDispose | boolean | eğer true olarak ayarlanmışsa  [kapatma gerekir]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | eğer true olarak ayarlanmışsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenmesinde çökmesine neden olabileceğini unutmayın. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Belirtilen konum için bir görüntü pikseli ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| color | [Color](../../com.aspose.psd/color) | Belirtilen konum için piksel rengi. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer görüntü bileşenleri önceden çarpılmış olmalıysa; aksi takdirde,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Özel renk dönüştürücüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Özel renk dönüştürücü |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Palet indeksi sınırların dışındaysa kullanılacak yedek indeks |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


İndeksli renk dönüştürücüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | İndeksli renk dönüştürücü |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin çözünürlüğünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | RasterImage'ın yatay çözünürlüğü, inç başına nokta (dpi) cinsinden. |
| dpiY | double | RasterImage'ın dikey çözünürlüğü, inç başına nokta (dpi) cinsinden. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. Doğru renk dönüşümü için CmykColorProfile ile eşleşmelidir.

Değer: RGB renk profili.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Döndürme modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Döndürme modu. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisini içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer: katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalı şeffaflık verisi içeriyorsa true, aksi takdirde false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Görüntünün şeffaf rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | XMP meta verileri güncelleniyorsa true; aksi takdirde false. |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Ham veri yükleme mevcut olduğunda ham veri yükleme kullanılıyorsa true; aksi takdirde false. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Girişim lisansını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Girişim lisansı. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) öğesinin dikey çözünürlüğünü, inç başına piksel cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP meta verilerini alır veya ayarlar.

Değer: XMP üst verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Raster görüntüyü bitmap'e dönüştürür.

**Returns:**
java.awt.image.BufferedImage - Bit eşlem
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |
| argb32Pixels | int[] | Yazılacak 32-bit ARGB renk dizisi. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Yazılacak piksel renkleri dizisi. |

