---
title: "PdfOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "PDF seçenekleri."
type: docs
weight: 18
url: /tr/java/com.aspose.psd.imageoptions/pdfoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

PDF seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Yeni bir [PdfOptions](../../com.aspose.psd.imageoptions/pdfoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu örneği klonlar. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getCorePdfOptions_internalized()](#getCorePdfOptions-internalized--) | PDF çekirdek seçeneklerini alır. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeve olup olmadığını gösteren bir değeri alır. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [getPageSize()](#getPageSize--) | Sayfanın boyutunu alır. |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | PDF çekirdek seçenekleri |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Belge için üst veriyi alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getSource()](#getSource--) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [getXmpData()](#getXmpData--) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam çerçeve olup olmadığını gösteren bir değeri ayarlar. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Sayfanın boyutunu ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.psd.fileformats.pdf.PdfCoreOptions-) | PDF çekirdek seçenekleri |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.psd.fileformats.pdf.PdfDocumentInfo-) | Belge için üst veriyi alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Yeni bir [PdfOptions](../../com.aspose.psd.imageoptions/pdfoptions) sınıfı örneği başlatır.

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
### getCorePdfOptions_internalized() {#getCorePdfOptions-internalized--}
```
public PdfOptionsCore getCorePdfOptions_internalized()
```


PDF çekirdek seçeneklerini alır.

**Returns:**
com.aspose.foundation.rendering.pdf.PdfOptionsCore
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
### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Sayfanın boyutunu alır.

Değer: Sayfanın boyutu.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the size of the page.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır veya ayarlar.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


PDF çekirdek seçenekleri

**Returns:**
[PdfCoreOptions](../../com.aspose.psd.fileformats.pdf/pdfcoreoptions)
### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Belge için üst veriyi alır veya ayarlar.

**Returns:**
[PdfDocumentInfo](../../com.aspose.psd.fileformats.pdf/pdfdocumentinfo)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


İlerleme olayı işleyicisini alır veya ayarlar.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
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

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public final void setPageSize(SizeF value)
```


Sayfanın boyutunu ayarlar.

Değer: Sayfanın boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | sayfanın boyutu. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.psd.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


PDF çekirdek seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.psd.fileformats.pdf/pdfcoreoptions) |  |

### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.psd.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Belge için üst veriyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.psd.fileformats.pdf/pdfdocumentinfo) |  |

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

