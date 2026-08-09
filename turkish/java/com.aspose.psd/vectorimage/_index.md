---
title: "VectorImage"
second_title: "Java için Aspose.PSD API Referansı"
description: "Vektör görüntüsü, tüm vektör görüntü türleri için temel sınıftır."
type: docs
weight: 111
url: /tr/java/com.aspose.psd/vectorimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.interfaces.IObjectWithSizeF](../../com.aspose.psd.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

Vektör görüntüsü, tüm vektör görüntü türleri için temel sınıftır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VectorImage()](#VectorImage--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Görüntü yüklendiğinde meydana gelir |
| [OnLoad_internalized](#OnLoad-internalized) | Görüntü createFirstSupportedLoader tarafından yüklendiğinde meydana gelir |
| [OnSave_internalized](#OnSave-internalized) | Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Kredi kullanıldığında meydana gelir |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel DataStreamSupporter.DataStreamContainer'dan ek veri yüklemesinin yapılmayacağını garanti eder. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen loadOptions kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps'ye dönüştürür. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Otomatik palet ayarlamasının olup olmadığını gösteren bir değer alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getBounds()](#getBounds--) | Görüntünün sınırlarını alır. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Görüntü konteynerini alır. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Nesnenin veri akışını alır. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Derinlemesine palet ayarlamasını alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Dosya formatını alır. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Dosya formatını alır. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Dosya formatını alır. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getHeight()](#getHeight--) | Görüntü yüksekliğini alır. |
| [getHeightF()](#getHeightF--) | Nesnenin yüksekliğini, inç cinsinden alır. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Kesinti izleyicisini alır. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Bellek yöneticisini alır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Boyanabilir görüntüyü alır. |
| [getPalette()](#getPalette--) | Renk paletini alır. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Özel yazı tipi önbelleğini oluşturur. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | İlerleme olayı işleyici bilgilerini alır. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Orantılı bir yüksekliği alır. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Orantılı bir genişliği alır. |
| [getSize()](#getSize--) | Görüntü boyutunu alır. |
| [getSizeF()](#getSizeF--) | Nesnenin boyutunu, inç cinsinden alır. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Kaynak görüntünün dosya yolunu, mevcutsa alır. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Girişim lisansını alır. |
| [getWidth()](#getWidth--) | Görüntü genişliğini alır. |
| [getWidthF()](#getWidthF--) | Nesnenin genişliğini, inç cinsinden alır. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değeri alır. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | İlerleme maksimum değerini alır veya ayarlar |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | İlerlemeyi gösterir. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer alır. |
| [isUsePalette()](#isUsePalette--) | Görüntü paletinin kullanılıp kullanılmadığını belirten bir değeri alır. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(String filePath)](#load-java.lang.String-) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Bu [Image](../../com.aspose.psd/image) kapsayıcısı ayarlandığında çağırılır. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Görüntünün boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntünün boyutunu değiştirir. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Otomatik palet ayarlaması olup olmadığını gösteren bir değer ayarlar. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Görüntü konteynerini ayarlar. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Nesnenin veri akışını ayarlar. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Bu görüntü örneğinin yüklemeden sonra değişip değişmediğini belirten bir değeri alır veya ayarlar. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Kesinti izleyiciyi ayarlar. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Bellek yöneticisini ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini ayarlar. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tüm Aspose ürünleri bu yöntemi uygulamalıdır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorImage() {#VectorImage--}
```
public VectorImage()
```


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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


aps'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |
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
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
public abstract int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntü yüksekliğini alır.

**Returns:**
int - görüntünün yüksekliği.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Nesnenin yüksekliğini, inç cinsinden alır.

**Returns:**
float - nesnenin yüksekliği, inç cinsinden.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Kesinti izleyicisini alır.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Bellek yöneticisini alır.

Değer: Bellek yöneticisi.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - bellek yöneticisi.
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
### getSize() {#getSize--}
```
public Size getSize()
```


Görüntü boyutunu alır.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


Nesnenin boyutunu, inç cinsinden alır.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the object size, in inches.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Kaynak görüntünün dosya yolunu varsa alır. Kaynak yol bulunamazsa boş bir dize döndürür.

**Returns:**
java.lang.String - Kaynak görüntünün dosya yolu.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır.

Value:  true  eğer nesne bellek optimizasyon stratejisi kullanıyorsa; aksi takdirde,  false .

**Returns:**
boolean - nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını gösteren bir değer
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Girişim lisansını alır.

**Returns:**
java.lang.Object - Giriş lisansı nesne olarak.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntü genişliğini alır.

**Returns:**
int - görüntünün genişliği.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Nesnenin genişliğini, inç cinsinden alır.

**Returns:**
float - nesnenin genişliği, inç cinsinden.
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer alır.

**Returns:**
boolean - nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer.
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Görüntü paletinin kullanılıp kullanılmadığını belirten bir değeri alır.

Value:  true  eğer palet görüntüde kullanılıyorsa; aksi takdirde,  false .

**Returns:**
boolean - görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer.
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Rotate flip'in türü. |

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




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Görüntü konteynerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Görüntü kapsayıcısı. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Nesnenin veri akışını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Nesnenin veri akışı. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Kesinti izleyiciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | kesinti izleyicisi. |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | eğer true olarak ayarlanmışsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenmesinde çökmesine neden olabileceğini unutmayın. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Tüm Aspose ürünleri bu yöntemi uygulamalıdır. Bu yöntem, bir GroupDocs ürünü tarafından GroupDocs'un lisanslı olup olmadığını göstermek ve özel bir filigran belirtmek için çağrılır. GroupDocs lisanslı olduğunda, bu belge örneği de Aspose ürünü lisanslı olmasa bile lisanslı gibi davranmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

