---
title: "PngOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "PNG dosya formatı oluşturma seçenekleri."
type: docs
weight: 19
url: /tr/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

PNG dosya formatı oluşturma seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngOptions()](#PngOptions--) | PngOptions sınıfının yeni bir örneğini başlatır. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | JpegOptions sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Varsayılan sıkıştırma seviyesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu örneği klonlar. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Bit derinliğini alır. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Rengin türünü alır veya ayarlar. |
| [getCompressionLevel()](#getCompressionLevel--) | 0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFilterType()](#getFilterType--) | png dosyası kaydetme sürecinde kullanılan filtre tipini alır veya ayarlar. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeve olup olmadığını gösteren bir değeri alır. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [getProgressive()](#getProgressive--) | Bu PngOptions'ın ilerlemeli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getSource()](#getSource--) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [getXmpData()](#getXmpData--) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Bit derinliğini ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | Rengin türünü alır veya ayarlar. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [setFilterType(int value)](#setFilterType-int-) | png dosyası kaydetme sürecinde kullanılan filtre tipini alır veya ayarlar. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam çerçeve olup olmadığını gösteren bir değeri ayarlar. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Bu PngOptions'ın ilerlemeli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | Seçenek doğrulama rutini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


PngOptions sınıfının yeni bir örneğini başlatır.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


JpegOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | PNG seçenekleri. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Varsayılan sıkıştırma seviyesi.

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Bu örneği klonlar.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Bit derinliğini alır.

**Returns:**
byte - Bit derinliği.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Rengin türünü alır veya ayarlar.

**Returns:**
int - Renk türü.
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur.

**Returns:**
int - 0-9 aralığındaki sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Varsayılan değiştirme yazı tipini alır veya ayarlar (yazı tipi, rastera dışa aktarırken metin çizerken kullanılacak, PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Değer: Varsayılan değiştirme yazı tipi.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


png dosyası kaydetme sürecinde kullanılan filtre tipini alır veya ayarlar.

**Returns:**
int - png dosyası kaydetme sürecinde kullanılan filtre tipi.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Tam çerçeve olup olmadığını gösteren bir değeri alır.

Değer:  true  eğer [full frame]; aksi takdirde,  false .

**Returns:**
boolean - [full frame] olup olmadığını gösteren bir değer.
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar.

Değer:  true  oluşturma olayından sonra yok sayılırsa; aksi takdirde,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Çok sayfalı seçenekler

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır veya ayarlar.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


İlerleme olayı işleyicisini alır veya ayarlar.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Bu PngOptions'ın ilerlemeli olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - ilerlemeli ise true; aksi takdirde false.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Çözünürlük ayarlarını alır veya ayarlar.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Görselin oluşturulacağı kaynağı alır veya ayarlar.

Değer: Görüntünün oluşturulacağı kaynak.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP meta veri kapsayıcısını alır veya ayarlar.

Değer: XMP veri kapsayıcısı.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Bit derinliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Bit derinliği. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Rengin türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Renk türü. |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | 0-9 aralığındaki sıkıştırma seviyesi, 9 en yüksek sıkıştırma ve 0 saklama modudur. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Varsayılan değiştirme yazı tipini alır veya ayarlar (yazı tipi, rastera dışa aktarırken metin çizerken kullanılacak, PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Değer: Varsayılan değiştirme yazı tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


png dosyası kaydetme sürecinde kullanılan filtre tipini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | png dosyası kaydetme sürecinde kullanılan filtre tipi. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Tam çerçeve olup olmadığını gösteren bir değeri ayarlar.

Değer:  true  eğer [full frame]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [full frame] olup olmadığını gösteren bir değer. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar.

Değer:  true  oluşturma olayından sonra yok sayılırsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Çok sayfalı seçenekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


İlerleme olayı işleyicisini alır veya ayarlar.

Değer: İlerleme olayı işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Bu PngOptions'ın ilerlemeli olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | doğru ise ilerleyici; aksi takdirde, yanlış. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Çözünürlük ayarlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Görselin oluşturulacağı kaynağı alır veya ayarlar.

Değer: Görüntünün oluşturulacağı kaynak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP meta veri kapsayıcısını alır veya ayarlar.

Değer: XMP veri kapsayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


Seçenek doğrulama rutini.

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

