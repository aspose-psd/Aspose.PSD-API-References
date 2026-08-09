---
title: "ThresholdLayer"
second_title: "Java için Aspose.PSD API Referansı"
description: "Eşik Ayarlama Katmanı."
type: docs
weight: 29
url: /tr/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer)
```
public class ThresholdLayer extends AdjustmentLayer
```

Eşik Ayarlama Katmanı.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BlendSignature](#BlendSignature) | Karışım modu imzasını temsil eder. |
| [LayerHeaderSize](#LayerHeaderSize) | Katman başlığı boyutu. |
| [OnCreate_internalized](#OnCreate-internalized) | Görüntü yüklendiğinde meydana gelir |
| [OnLoad_internalized](#OnLoad-internalized) | Görüntü createFirstSupportedLoader tarafından yüklendiğinde meydana gelir |
| [OnSave_internalized](#OnSave-internalized) | Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Kredi kullanıldığında meydana gelir |
| [resources_internalized](#resources-internalized) | Kaynaklar |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Belirtilen türle ilişkili kaynağı alır. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Maskeyi mevcut katmana ekler. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Kaynağı ekler. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını ayarlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Görüntü kontrastı |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Bir görüntünün gama düzeltmesi. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi. |
| [applyLayerMask()](#applyLayerMask--) | Katman maskesini katmana uygular, ardından maskeyi siler. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Girdi [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) katman stil ayarını mevcut [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) örneğine uygular. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps'ye dönüştürür. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) sınıfının yeni bir örneğini oluşturur. |
| [createLayerState_internalized()](#createLayerState-internalized--) | Mevcut [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) değerlerine dayanarak yeni [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) örneğini oluşturur. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader psdHeader, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
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
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Görüntüyü katmana çizer. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgeni filtreler. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Atanabilir kaynağı bulur. |
| [findPattResource_internalized()](#findPattResource-internalized--) | PattResource'ı bulur |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Kaynağı benzersiz anahtara göre bulur |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Mutlak sınırları alır veya ayarlar. |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | Ayarlama katmanının tipini alır. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Otomatik palet ayarlamasının olup olmadığını gösteren bir değer alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Kırpılmış öğenin karışımını alır veya ayarlar. |
| [getBlendModeKey()](#getBlendModeKey--) | Karışım modu anahtarını alır veya ayarlar. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Karışım modu imzasını alır. |
| [getBlendingOptions()](#getBlendingOptions--) | Karışım seçeneklerini alır. |
| [getBottom()](#getBottom--) | Alt katmanın konumunu alır veya ayarlar. |
| [getBounds()](#getBounds--) | Görüntünün sınırlarını alır. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Tam maske modu için satır başına bayt sayısını alır. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Satır başına bayt sayısını alır. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Satır başına bayt sayısını alır. |
| [getChannelInformation()](#getChannelInformation--) | Kanal bilgilerini alır veya ayarlar. |
| [getChannelsCount()](#getChannelsCount--) | Katmanın kanal sayısını alır. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Katman kırpmasını alır veya ayarlar. |
| [getContainer()](#getContainer--) | Görüntü konteynerini alır. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Nesnenin veri akışını alır. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Derinlemesine palet ayarlamasını alır. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Kısmi piksel yükleyicisi kullanarak varsayılan piksel dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Kısmi piksel yükleyicisi kullanarak varsayılan ham veri dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Varsayılan ham veri dizisini alır. |
| [getDisplayName()](#getDisplayName--) | Katmanın görüntüleme adını alır. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getExtraLength()](#getExtraLength--) | Katmanın ek bilgi uzunluğunu bayt cinsinden alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Dosya formatını alır. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Dosya formatını alır. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Dosya formatını alır. |
| [getFillOpacity()](#getFillOpacity--) | Dolgu opaklığını alır veya ayarlar. |
| [getFiller()](#getFiller--) | Katman doldurucusunu alır veya ayarlar. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFlags()](#getFlags--) | Katman bayraklarını alır veya ayarlar. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Geçerli katmanın [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) klasör hiyerarşisi listesini alır. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Biçim‑özel yerlerden paleti alır |
| [getGUID_internalized()](#getGUID-internalized--) | Bu Katman örneğinin benzersiz tanımlayıcısını alır. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getHeight()](#getHeight--) | Görüntü yüksekliğini alır. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu RasterImage'ın inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| [getImageOpacity()](#getImageOpacity--) | Bu görüntünün opaklığını alır. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | İç veri dönüştürücüyü alır. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Kesinti izleyicisini alır. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Katman karıştırma aralıkları verisini alır veya ayarlar. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Katman oluşturma tarih‑zamanını alır veya ayarlar. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Katman kilidini alır veya ayarlar. |
| [getLayerMaskData()](#getLayerMaskData--) | Katman maske verisini alır veya ayarlar. |
| [getLayerOptions()](#getLayerOptions--) | Katman seçeneklerini alır. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Katman paletini alır veya ayarlar. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Katmanın tipini alır. |
| [getLeft()](#getLeft--) | Sol katman konumunu alır veya ayarlar. |
| [getLength()](#getLength--) | Katmanın toplam uzunluğunu bayt cinsinden alır. |
| [getLevel()](#getLevel--) | Eşik seviyesini alır ve ayarlar. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Bellek yöneticisini alır. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Katman adını alır veya ayarlar. |
| [getOpacity()](#getOpacity--) | Katman opaklığını alır veya ayarlar. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Toplam opaklığı alır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Boyanabilir görüntüyü alır. |
| [getPalette()](#getPalette--) | Renk paletini alır. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Bir görüntü pikselini alır. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Özel yazı tipi önbelleğini oluşturur. |
| [getProcessor_internalized()](#getProcessor-internalized--) | İşlemciyi alır. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Orantılı bir yüksekliği alır. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Orantılı bir genişliği alır. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Özel renk dönüştürücüyü alır veya ayarlar. |
| [getRawDataFormat()](#getRawDataFormat--) | Ham veri biçimini alır. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | İndeksli renk dönüştürücüyü alır veya ayarlar. |
| [getRawLineSize()](#getRawLineSize--) | Ham satır boyutunu bayt cinsinden alır. |
| [getResources()](#getResources--) | Katman kaynaklarını alır veya ayarlar. |
| [getRight()](#getRight--) | Sağ katman konumunu alır veya ayarlar. |
| [getRotateMode()](#getRotateMode--) | Döndürme modunu alır veya ayarlar. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Katmanlar listesindeki dekoratif sayfa renk vurgusunu alır veya ayarlar |
| [getSize()](#getSize--) | Görüntü boyutunu alır. |
| [getSkewAngle()](#getSkewAngle--) | Eğim açısını alır. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Kaynak görüntünün dosya yolunu, mevcutsa alır. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Senkronizasyon kökünü alır. |
| [getTop()](#getTop--) | Üst katman konumunu alır veya ayarlar. |
| [getTransparentColor()](#getTransparentColor--) | Görüntünün şeffaf rengini alır. |
| [getUpdateXmpData()](#getUpdateXmpData--) | XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır. |
| [getUseRawData()](#getUseRawData--) | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Kullanılan paleti alır. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Girişim lisansını alır. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [getWidth()](#getWidth--) | Görüntü genişliğini alır. |
| [getXmpData()](#getXmpData--) | XMP meta verilerini alır veya ayarlar. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini belirten bir değeri alır. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değeri alır. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | İlerleme maksimum değerini alır veya ayarlar |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | İlerlemeyi gösterir. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Resources koleksiyonuna bir kaynak ekler. |
| [isCached()](#isCached--) | Görüntü verisinin şu anda önbelleğe alınıp alınmadığını belirten bir değeri alır. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Katmanın dosyaya kaydedilmesi için geçerli olup olmadığını algılar. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ham veri yüklemesinin mevcut olup olmadığını belirten bir değeri alır. |
| [isUsePalette()](#isUsePalette--) | Görüntü paletinin kullanılıp kullanılmadığını belirten bir değeri alır. |
| [isVisible()](#isVisible--) | Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar |
| [isVisibleInGroup()](#isVisibleInGroup--) | Bu örneğin grup içinde görünür olup olmadığını gösteren bir değeri alır (Katman grup içinde değilse, kök grup anlamına gelir). |
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
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Katmanı belirtilen katmana birleştirir |
| [normalizeAngle()](#normalizeAngle--) | Açıyı normalleştirir. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Açıyı normalleştirir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Bu Image'ın kapsayıcısı ayarlandığında çağırılır. |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Threshold katmanını işler. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Kaynağı kaldırır. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | İzin verilen farkla bir rengi diğerine değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntünün boyutunu değiştirir. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Verileri birleştirir. |
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
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Veriyi belirtilen akış konteynerine kaydeder. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Mutlak sınırları alır veya ayarlar. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Otomatik palet ayarlaması olup olmadığını gösteren bir değer ayarlar. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Kırpılmış öğenin karışımını alır veya ayarlar. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Karışım modu anahtarını alır veya ayarlar. |
| [setBottom(int value)](#setBottom-int-) | Alt katmanın konumunu alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Kanal bilgilerini alır veya ayarlar. |
| [setClipping(byte value)](#setClipping-byte-) | Katman kırpmasını alır veya ayarlar. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Görüntü konteynerini ayarlar. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Veri yükleyiciyi doğrudan ayarlar. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Nesnenin veri akışını ayarlar. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Katmanın görüntüleme adını alır veya ayarlar. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Dolgu opaklığını alır. |
| [setFiller(byte value)](#setFiller-byte-) | Katman doldurucusunu alır veya ayarlar. |
| [setFlags(byte value)](#setFlags-byte-) | Katman bayraklarını alır veya ayarlar. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Paleti biçim‑özel yerlerine ayarlar |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu RasterImage'ın inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | İç veri dönüştürücüyü ayarlar. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Kesinti izleyiciyi ayarlar. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Katman karıştırma aralıkları verisini alır veya ayarlar. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Katman oluşturma tarih‑zamanını alır veya ayarlar. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Katman kilidini alır veya ayarlar (Not: eğer LayerFlags.TransparencyProtected bayrağı ayarlıysa, katman kilidi bayrağı tarafından üzerine yazılacaktır. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Katman maske verisini alır veya ayarlar. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Katman paletini alır veya ayarlar. |
| [setLeft(int value)](#setLeft-int-) | Sol katman konumunu alır veya ayarlar. |
| [setLevel(short value)](#setLevel-short-) | Eşik seviyesini alır ve ayarlar. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Kısmi döndürme kaydı için izin verilen maksimum tahsisi alır veya ayarlar. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Bellek yöneticisini ayarlar. |
| [setName(String name)](#setName-java.lang.String-) | Katman adını ayarlar. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Katman adını alır veya ayarlar. |
| [setOpacity(byte value)](#setOpacity-byte-) | Katman opaklığını alır veya ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini ayarlar. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Özel renk dönüştürücüyü alır veya ayarlar. |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Palet indeksi sınırların dışına çıktığında kullanılacak geri dönüş indeksini alır veya ayarlar. |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | İndeksli renk dönüştürücüyü alır veya ayarlar. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Bu RasterImage için çözünürlüğü ayarlar. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Katman kaynaklarını alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Sağ katman konumunu alır veya ayarlar. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Döndürme modunu alır veya ayarlar. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Katmanlar listesindeki dekoratif sayfa renk vurgusunu alır veya ayarlar |
| [setTop(int value)](#setTop-int-) | Üst katman konumunu alır veya ayarlar. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Görüntünün şeffaf rengini alır. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | XMP meta verilerini güncelleme gerekip gerekmediğini belirten bir değeri alır veya ayarlar. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını belirten bir değeri alır veya ayarlar. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tüm Aspose ürünleri bu yöntemi uygulamalıdır. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta verilerini alır veya ayarlar. |
| [shallowCopy()](#shallowCopy--) | Mevcut Layer'ın yüzeysel bir kopyasını oluşturur. |
| [toBitmap()](#toBitmap--) | Raster görüntüyü bitmap'e dönüştürür. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Katman veya global kaynaklar değiştikten sonra karıştırma seçeneklerini günceller. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Karışım modu imzasını temsil eder.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


Katman başlığı boyutu.

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Kaynaklar

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Belirtilen türle ilişkili kaynağı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | Bu yöntem döndüğünde, anahtar bulunursa belirtilen anahtar türüyle ilişkili kaynağı içerir; aksi takdirde null döndürür. |

T : Alınacak değerin anahtar türü. |

**Returns:**
boolean -   belirtilen türde bir kaynak içeriyorsa; aksi takdirde,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Maskeyi mevcut katmana ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Katman maskesi. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Kaynağı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Kaynak. |

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

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Katman maskesini katmana uygular, ardından maskeyi siler.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Girdi [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) katman stil ayarını mevcut [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) örneğine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | Yeni stil ile katman durumu. |

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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | Başlık. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | Bu LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Mevcut [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) değerlerine dayanarak yeni [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) örneğini oluşturur.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
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
### create_internalized(PsdHeader psdHeader, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static ThresholdLayer create_internalized(PsdHeader psdHeader, LayerResource[] resources)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Görüntüyü katmana çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Konum. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Görüntü. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak Object. |

**Returns:**
boolean -  true  eğer belirtilen Object bu örnek ile eşitse; aksi takdirde,  false .
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

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Atanabilir kaynağı bulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | com.aspose.ms.System.Type | Tür. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


PattResource'ı bulur

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Kaynağı benzersiz anahtara göre bulur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeToolKey | int | Tür aracı anahtarı. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Mutlak sınırları alır veya ayarlar.

Değer: Mutlak sınırlar.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


Ayarlama katmanının tipini alır.

Değer: Ayarlama katmanının tipi.

**Returns:**
byte
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Kırpılmış öğenin karışımını alır veya ayarlar.

Değer: Kesilmiş öğenin karıştırılması.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Karışım modu anahtarını alır veya ayarlar.

Değer: Karışım modu anahtarı.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Karışım modu imzasını alır.

Değer: Karışım modu imzası.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Karışım seçeneklerini alır.

Değer: Karıştırma seçenekleri.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Alt katmanın konumunu alır veya ayarlar.

Değer: Alt katman konumu.

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Tam maske modu için satır başına bayt sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitDepth | int | Bit derinliği. |

**Returns:**
int - 1 satırı depolamak için gereken bayt sayısı
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Satır başına bayt sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitDepth | int | Bit derinliği. |

**Returns:**
int - 1 satırı depolamak için gereken bayt sayısı
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Satır başına bayt sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitDepth | int | Bit derinliği. |

**Returns:**
int - 1 satırı depolamak için gereken bayt sayısı
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Kanal bilgilerini alır veya ayarlar.

Değer: Kanal bilgisi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Katmanın kanal sayısını alır.

Değer: Katmanın kanal sayısı.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Katman kırpmasını alır veya ayarlar. 0 = temel, 1 = temel dışı.

Değer: Katman kırpması.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Görüntü konteynerini alır.

Değer: Image konteyneri.

Bu özellik null değilse, görüntünün başka bir görüntü içinde bulunduğunu gösterir.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Katmanın görüntüleme adını alır.

Değer: Katmanın görüntüleme adı.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Katmanın ek bilgi uzunluğunu bayt cinsinden alır.

Değer: Ek katman uzunluğu.

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Dolgu opaklığını alır veya ayarlar.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Katman doldurucusunu alır veya ayarlar.

Değer: Katman doldurucu.

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Katman bayraklarını alır veya ayarlar. bit 0 = şeffaflık korumalı; bit 1 = görünür; bit 2 = eski; bit 3 = Photoshop 5.0 ve sonrası için 1, bit 4'ün faydalı bilgi içerip içermediğini belirtir; bit 4 = belge görünümüne alakasız piksel verisi.

Değer: Katman bayrakları.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Geçerli katmanın [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) klasör hiyerarşisi listesini alır.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Mevcut katmanın klasör hiyerarşisi olan [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) listesini döndürür.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Biçim‑özel yerlerden paleti alır

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Bu Katman örneğinin benzersiz tanımlayıcısını alır.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Bu RasterImage'ın inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar.

**Returns:**
double - Yatay çözünürlük.

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Bu görüntünün opaklığını alır.

**Returns:**
float - Opaklık değeri 0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında.
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
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Katman karıştırma aralıkları verisini alır veya ayarlar.

Değer: Katman karıştırma aralıkları verisi.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Katman oluşturma tarih‑zamanını alır veya ayarlar.

Değer: Katmanın oluşturulma tarih ve saati. Oluşturma DateTime'ı hakkında veri yoksa Unix Zamanı'nın ilk dönemi döndürülür.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Katman kilidini alır veya ayarlar. LayerFlags.TransparencyProtected bayrağı ayarlanmışsa, katman kilidi bayrağı tarafından üzerine yazılacağını unutmayın. LayerFlags.TransparencyProtected bayrağını geri döndürmek için katman seçeneğine layer.Flags |= LayerFlags.TransparencyProtected uygulanmalıdır.

Değer: Katman kilidi.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Katman maske verisini alır veya ayarlar.

Değer: Katman maskesi verisi.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Katman seçeneklerini alır.

Değer: Katman seçenekleri.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Katman paletini alır veya ayarlar.

Değer: Katman paleti.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Katmanın tipini alır.

Değer: Katmanın türü.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Sol katman konumunu alır veya ayarlar.

Değer: Sol katman konumu.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Katmanın toplam uzunluğunu bayt cinsinden alır.

**Returns:**
long
### getLevel() {#getLevel--}
```
public final short getLevel()
```


Eşik seviyesini alır ve ayarlar.

Değer: Seviye.

**Returns:**
short
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
### getName() {#getName--}
```
public final String getName()
```


Katman adını alır veya ayarlar.

Değer: Katman adı.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Katman opaklığını alır veya ayarlar. 0 = şeffaf, 255 = opak.

Değer: Katman opaklığı.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Toplam opaklığı alır. Toplam opaklık, Layer Opacity ve Layer Fill Opacity'nin çarpımıdır. Katman karıştırma için kullanılır.

Değer: Toplam opaklık.

**Returns:**
byte
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
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


İşlemciyi alır.

Değer: İşlemci.

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Katman kaynaklarını alır veya ayarlar.

Value: Katman kaynakları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Sağ katman konumunu alır veya ayarlar.

Value: Sağ katman konumu.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Döndürme modunu alır veya ayarlar.

**Returns:**
int - Döndürme modu.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Katmanlar listesindeki dekoratif sayfa renk vurgusunu alır veya ayarlar

Value: Sayfa renk vurgusu.

**Returns:**
short
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Kaynak görüntünün dosya yolunu varsa alır. Kaynak yol bulunamazsa boş bir dize döndürür.

**Returns:**
java.lang.String - Kaynak görüntünün dosya yolu.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Senkronizasyon kökünü alır.

Value: Senkronizasyon kökü.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Üst katman konumunu alır veya ayarlar.

Value: Üst katman konumu.

**Returns:**
int
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar.

**Returns:**
double - Dikey çözünürlük.

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Bir görüntünün gri tonlamalı temsiline dönüşümü

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini belirten bir değeri alır.

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

**Returns:**
boolean -  true  eğer bu örnek görüntüsü değişmişse; aksi takdirde,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Görüntünün şeffaf renge sahip olup olmadığını belirten bir değeri alır.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Resources koleksiyonuna bir kaynak ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Eklenmesi gereken kaynağın indeksi. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Eklenmesi gereken kaynak. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Görüntü verisinin şu anda önbelleğe alınıp alınmadığını belirten bir değeri alır.

**Returns:**
boolean -  true  eğer görüntü verisi önbelleğe alınmışsa; aksi takdirde,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Katmanın dosyaya kaydedilmesi için geçerli olup olmadığını algılar.

**Returns:**
boolean -
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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Bu örneğin grup içinde görünür olup olmadığını gösteren bir değeri alır (Katman grup içinde değilse, kök grup anlamına gelir).

Value:  true  eğer bu örnek grup içinde görünürse; aksi takdirde,  false .

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Katmanı belirtilen katmana birleştirir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Birleştirilecek katman. |

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


Bu Image'ın kapsayıcısı ayarlandığında çağırılır.

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Threshold katmanını işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel dikdörtgeni. |
| piksel | int[] | Piksel dizisi. |
| start | [Point](../../com.aspose.psd/point) | Piksel sol üst konumu. |
| end | [Point](../../com.aspose.psd/point) | Piksel sağ alt konumu. |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle> - Piksellerin dikdörtgeni ve işlenen pikseller.
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
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Kaynağı kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Kaynak. |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Verileri birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Dikdörtgen. |

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

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verisini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırları kullanmak için boş dikdörtgen ayarlayın. |

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

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Veriyi belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| psdVersion | int | PSD sürümü. |
| bitDepth | int | Bit derinliği. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Mutlak sınırları alır veya ayarlar.

Değer: Mutlak sınırlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Kırpılmış öğenin karışımını alır veya ayarlar.

Değer: Kesilmiş öğenin karıştırılması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Karışım modu anahtarını alır veya ayarlar.

Değer: Karışım modu anahtarı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Alt katmanın konumunu alır veya ayarlar.

Değer: Alt katman konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Kanal bilgilerini alır veya ayarlar.

Değer: Kanal bilgisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Katman kırpmasını alır veya ayarlar. 0 = temel, 1 = temel dışı.

Değer: Katman kırpması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Katmanın görüntüleme adını alır veya ayarlar.

Değer: Katmanın görüntüleme adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Dolgu opaklığını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Katman doldurucusunu alır veya ayarlar.

Değer: Katman doldurucu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Katman bayraklarını alır veya ayarlar. bit 0 = şeffaflık korumalı; bit 1 = görünür; bit 2 = eski; bit 3 = Photoshop 5.0 ve sonrası için 1, bit 4'ün faydalı bilgi içerip içermediğini belirtir; bit 4 = belge görünümüne alakasız piksel verisi.

Değer: Katman bayrakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu RasterImage'ın inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

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

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Katman karıştırma aralıkları verisini alır veya ayarlar.

Değer: Katman karıştırma aralıkları verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Katman oluşturma tarih‑zamanını alır veya ayarlar.

Değer: Katmanın oluşturulma tarih ve saati. Oluşturma DateTime'ı hakkında veri yoksa Unix Zamanı'nın ilk dönemi döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Katman kilidini alır veya ayarlar (Not: eğer LayerFlags.TransparencyProtected bayrağı ayarlıysa, katman kilidi bayrağı tarafından üzerine yazılacaktır. LayerFlags.TransparencyProtected bayrağını geri döndürmek için katman seçeneğine layer.Flags |= LayerFlags.TransparencyProtected uygulanmalıdır

Değer: Katman kilidi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Katman maske verisini alır veya ayarlar.

Değer: Katman maskesi verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Katman paletini alır veya ayarlar.

Değer: Katman paleti.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Sol katman konumunu alır veya ayarlar.

Değer: Sol katman konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLevel(short value) {#setLevel-short-}
```
public final void setLevel(short value)
```


Eşik seviyesini alır ve ayarlar.

Değer: Seviye.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Katman adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Katman adı. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Katman adını alır veya ayarlar.

Değer: Katman adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Katman opaklığını alır veya ayarlar. 0 = şeffaf, 255 = opak.

Değer: Katman opaklığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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


Bu RasterImage için çözünürlüğü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | RasterImage'ın yatay çözünürlüğü, inç başına nokta (dpi) cinsinden. |
| dpiY | double | RasterImage'ın dikey çözünürlüğü, inç başına nokta (dpi) cinsinden. |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Katman kaynaklarını alır veya ayarlar.

Value: Katman kaynakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Sağ katman konumunu alır veya ayarlar.

Value: Sağ katman konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Döndürme modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Döndürme modu. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Katmanlar listesindeki dekoratif sayfa renk vurgusunu alır veya ayarlar

Value: Sayfa renk vurgusu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Üst katman konumunu alır veya ayarlar.

Value: Üst katman konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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


Tüm Aspose ürünleri bu yöntemi uygulamalıdır. Bu yöntem, bir GroupDocs ürünü tarafından GroupDocs'un lisanslı olup olmadığını göstermek ve özel bir filigran belirtmek için çağrılır. GroupDocs lisanslı olduğunda, bu belge örneği de Aspose ürünü lisanslı olmasa bile lisanslı gibi davranmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ventureLicense | java.lang.Object | lisans |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu RasterImage'ın inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP meta verilerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP meta verileri. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Mevcut Katmanın sığ bir kopyasını oluşturur. Açıklama için lütfen   .

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
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
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Katman veya global kaynaklar değiştikten sonra karıştırma seçeneklerini günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

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

