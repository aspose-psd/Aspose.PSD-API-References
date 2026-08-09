---
title: "GifOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "GIF dosya formatı oluşturma seçenekleri."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

GIF dosya formatı oluşturma seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions sınıfının yeni bir örneğini başlatır. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | GifOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu örneği klonlar. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF arka plan renk indeksini alır veya ayarlar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | GIF renk çözünürlüğünü alır veya ayarlar. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeve olup olmadığını gösteren bir değeri alır. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [getInterlaced()](#getInterlaced--) | Görüntünün satır arası olması gerekiyorsa True. |
| [getMaxDiff()](#getMaxDiff--) | izin verilen maksimum piksel farkını alır veya ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF piksel en‑boy oranını alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getSource()](#getSource--) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [getXmpData()](#getXmpData--) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [hasTrailer()](#hasTrailer--) | GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF arka plan renk indeksini alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | GIF renk çözünürlüğünü alır veya ayarlar. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam çerçeve olup olmadığını gösteren bir değeri ayarlar. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Görüntünün satır arası olması gerekiyorsa True. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | izin verilen maksimum piksel farkını alır veya ayarlar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF piksel en‑boy oranını alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions sınıfının yeni bir örneğini başlatır.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


GifOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | GIF Seçenekleri. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF arka plan renk indeksini alır veya ayarlar.

**Returns:**
byte - GIF arka plan renk indeksi.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF renk çözünürlüğünü alır veya ayarlar.

**Returns:**
byte - renk çözünürlüğü.

Color Resolution - Orijinal görüntüde mevcut olan her bir birincil renk için bit sayısı, 1 eksik. Bu değer, grafikteki renklerin seçildiği tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti, görüntüyü oluşturmak için her bir birincil renk başına 4 bit içeriyordu. Bu değer, orijinal paletin zenginliğini göstermek için ayarlanmalıdır, hatta tüm paletin her rengi kaynak makinede mevcut olmasa bile.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer palet düzeltmesi uygulanıyorsa; aksi takdirde,  false .

Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak üzere analiz edileceği anlamına gelir (görüntü Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olacak ve sonuç görsel olarak daha iyidir.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Görüntünün satır arası olması gerekiyorsa True.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Maksimum izin verilen piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır. Sadece az kayıp oluştuğunda en iyi çalışır ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz. İzin verilen değer aralığı [0, 1000]'dir.

**Returns:**
int - İzin verilen değer aralığı.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF piksel en‑boy oranını alır veya ayarlar.

Pixel Aspect Ratio - Orijinal görüntüde pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri aşağıdaki formüle göre hesaplanır: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, 4:1 en geniş pikselden 1:4 en yüksek piksele kadar 1/64 artışlarla belirtmeye olanak tanır. Değerler : 0 - En‑boy oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

**Returns:**
byte - GIF piksel en‑boy oranı.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer GIF'in trailer'ı varsa; aksi takdirde,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer palet girişleri sıralanmışsa; aksi takdirde,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF arka plan renk indeksini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | GIF arka plan renk indeksi. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF renk çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte | Renk çözünürlüğü. |

Color Resolution - Orijinal görüntüdeki birincil renk başına mevcut bit sayısı, 1 eksik. Bu değer, grafikteki renklerin seçildiği tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin kaynak makinede mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true  eğer palet düzeltmesi uygulanmışsa; aksi takdirde,  false . |

Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak üzere analiz edileceği anlamına gelir (görüntü Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olacak ve sonuç görsel olarak daha iyidir. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Görüntünün satır arası olması gerekiyorsa True.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Maksimum izin verilen piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır. Sadece az kayıp oluştuğunda en iyi çalışır ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz. İzin verilen değer aralığı [0, 1000]'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | İzin verilen değer aralığı. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer palet girişleri sıralanmışsa; aksi takdirde,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF piksel en‑boy oranını alır veya ayarlar.

Pixel Aspect Ratio - Orijinal görüntüde pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri aşağıdaki formüle göre hesaplanır: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, 4:1 en geniş pikselden 1:4 en yüksek piksele kadar 1/64 artışlarla belirtmeye olanak tanır. Değerler : 0 - En‑boy oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | GIF piksel en‑boy oranı. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer GIF'in trailer'ı varsa; aksi takdirde,  false . |

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

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP veri kapsayıcısı. |

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

