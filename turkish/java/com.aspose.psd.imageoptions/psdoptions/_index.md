---
title: "PsdOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosya formatı oluşturma seçenekleri."
type: docs
weight: 21
url: /tr/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

PSD dosya formatı oluşturma seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır. |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu örneği klonlar. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Arka plan rengini alır veya ayarlar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [getChannelsCount()](#getChannelsCount--) | Renk kanalı sayısını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | psd renk modunu alır veya ayarlar. |
| [getCompressionMethod()](#getCompressionMethod--) | psd sıkıştırma yöntemini alır veya ayarlar. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeve olup olmadığını gösteren bir değeri alır. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [getPsdVersion()](#getPsdVersion--) | Dosya formatı sürümünü alır veya ayarlar. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılan [refresh image preview data] seçeneğini gösteren bir değeri alır veya ayarlar. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | - Remove the global text engine resource - seçeneğini gösteren bir değeri alır veya ayarlar. Bu, bazı metin katmanlı psd dosyaları için kullanılır; yalnızca işleme sonrasında Adobe Photoshop'ta açılamadığında (çoğunlukla eksik fontlarla ilgili metin katmanları) uygulanır. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getResources()](#getResources--) | psd kaynaklarını alır veya ayarlar. |
| [getSource()](#getSource--) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [getUpdateMetadata()](#getUpdateMetadata--) | [update metadata] gösteren bir değeri alır veya ayarlar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [getVersion()](#getVersion--) | psd dosya sürümünü alır veya ayarlar. |
| [getXmpData()](#getXmpData--) | XMP veri kapsayıcısını al veya ayarla |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | ColorMode özelliğinin atanıp atanmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Arka plan rengini alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Renk kanalı sayısını alır veya ayarlar. |
| [setColorMode(short value)](#setColorMode-short-) | psd renk modunu alır veya ayarlar. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | psd sıkıştırma yöntemini alır veya ayarlar. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam çerçeve olup olmadığını gösteren bir değeri ayarlar. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Dosya formatı sürümünü alır veya ayarlar. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılan [refresh image preview data] seçeneğini gösteren bir değeri alır veya ayarlar. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | - Remove the global text engine resource - seçeneğini gösteren bir değeri alır veya ayarlar. Bu, bazı metin katmanlı psd dosyaları için kullanılır; yalnızca işleme sonrasında Adobe Photoshop'ta açılamadığında (çoğunlukla eksik fontlarla ilgili metin katmanları) uygulanır. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | psd kaynaklarını alır veya ayarlar. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | [update metadata] gösteren bir değeri alır veya ayarlar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | psd dosya sürümünü alır veya ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP veri kapsayıcısını al veya ayarla |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Seçenekler. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Görüntü. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Renk kanalı başına bit sayısını alır veya ayarlar.

Değer: Renk kanalı başına bit sayısı.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Renk kanalı sayısını alır veya ayarlar.

Değer: Renk kanalı sayısı.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


psd renk modunu alır veya ayarlar.

Değer: Renk modu.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


psd sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir.

Değer: Dosya formatı sürümü.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


[refresh image preview data] seçeneğini gösteren bir değeri alır veya ayarlar - başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılır. Lütfen, metin katmanlarının son düzene çizilmesinin Compact Framework platformunda desteklenmediğini unutmayın.

Değer:  true  eğer [refresh image preview data]; aksi takdirde,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


- Remove the global text engine resource - seçeneğini gösteren bir değeri alır veya ayarlar - bazı metin katmanlı psd dosyaları için kullanılır; yalnızca işleme sonrasında Adobe Photoshop'ta açılamadığında (çoğunlukla eksik fontlarla ilgili metin katmanları). Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları izlemelidir: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen, bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın.

Değer:  true  eğer [remove global text engine resource]; aksi takdirde,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Çözünürlük ayarlarını alır veya ayarlar.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


psd kaynaklarını alır veya ayarlar. Değer: NULL ise - orijinal ImageResources kaydedilir (varsayılan davranış) Boş değil ise - bu özelliğe geçirilen kaynaklar + [required resources] kaydedilir. Boş ise - yalnızca [required resources] kaydedilir. Gerekli kaynaklar: ResolutionInfoResource, XmpResource

Değer: psd kaynakları.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Görselin oluşturulacağı kaynağı alır veya ayarlar.

Değer: Görüntünün oluşturulacağı kaynak.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


[update metadata] gösteren bir değeri alır veya ayarlar. Değer true ise, görüntü kaydedilirken meta veriler güncellenir.

Değer:  true  eğer [update metadata]; aksi takdirde,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


psd dosya sürümünü alır veya ayarlar.

Değer: psd dosya sürümü.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP veri kapsayıcısını al veya ayarla

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


ColorMode özelliğinin atanıp atanmadığını gösterir.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
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


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Renk kanalı başına bit sayısını alır veya ayarlar.

Değer: Renk kanalı başına bit sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Renk kanalı sayısını alır veya ayarlar.

Değer: Renk kanalı sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


psd renk modunu alır veya ayarlar.

Değer: Renk modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


psd sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir.

Değer: Dosya formatı sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


[refresh image preview data] seçeneğini gösteren bir değeri alır veya ayarlar - başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılır. Lütfen, metin katmanlarının son düzene çizilmesinin Compact Framework platformunda desteklenmediğini unutmayın.

Değer:  true  eğer [refresh image preview data]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


- Remove the global text engine resource - seçeneğini gösteren bir değeri alır veya ayarlar - bazı metin katmanlı psd dosyaları için kullanılır; yalnızca işleme sonrasında Adobe Photoshop'ta açılamadığında (çoğunlukla eksik fontlarla ilgili metin katmanları). Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları izlemelidir: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen, bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın.

Değer:  true  eğer [remove global text engine resource]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Çözünürlük ayarlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


psd kaynaklarını alır veya ayarlar. Değer: NULL ise - orijinal ImageResources kaydedilir (varsayılan davranış) Boş değil ise - bu özelliğe geçirilen kaynaklar + [required resources] kaydedilir. Boş ise - yalnızca [required resources] kaydedilir. Gerekli kaynaklar: ResolutionInfoResource, XmpResource

Değer: psd kaynakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


[update metadata] gösteren bir değeri alır veya ayarlar. Değer true ise, görüntü kaydedilirken meta veriler güncellenir.

Değer:  true  eğer [update metadata]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


psd dosya sürümünü alır veya ayarlar.

Değer: psd dosya sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP veri kapsayıcısını al veya ayarla

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

