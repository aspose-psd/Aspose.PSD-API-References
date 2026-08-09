---
title: "AutoMaskingGraphCutOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "GraphCut otomatik maskeleme seçenekleri."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut otomatik maskeleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Yeni bir [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Arka plan nesne sayısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Otomatik maskeleme argümanlarını ekle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Varsayılan darbeleri doldur. |
| [getArgs()](#getArgs--) | Segmentasyon algoritması için argümanları alır. |
| [getAssumedObjects()](#getAssumedObjects--) | Tahmin edilen nesneleri alır. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Arka plan değiştirme rengini alır. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri alır. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Birleştirilmiş nesneler dikdörtgenini alır. |
| [getDecompose()](#getDecompose--) | Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Varsayılan arka plan darbelerini alır. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Önceden hesaplanmış varsayılan ön plan darbelerini alır. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Varsayılan nesne dikdörtgenlerini alır. |
| [getExportOptions()](#getExportOptions--) | Görüntü dışa aktarma seçeneklerini alır. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Tüylenme yarıçapını alır. |
| [getMaskingArea()](#getMaskingArea--) | Maskeleme alanını alır. |
| [getMethod()](#getMethod--) | Segmentasyon yöntemini alır. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini alır. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Tahmin edilen nesneler koleksiyonunun insan nesneleri içerip içermediğini gösteren bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Segmentasyon algoritması için argümanları ayarlar. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Tahmin edilen nesneleri ayarlar. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Arka plan değiştirme rengini ayarlar. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri ayarlar. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Birleştirilmiş nesneler dikdörtgeni. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri ayarlar. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Varsayılan arka plan darbeleri. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Önceden hesaplanmış varsayılan ön plan darbeleri. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Varsayılan nesne dikdörtgenleri. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Görüntü dışa aktarma seçeneklerini ayarlar. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Tüylenme yarıçapını ayarlar. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Koleksiyonda varsayılan nesnelerin insan nesneleri içerip içermediğini gösteren bir değer. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Maskeleme alanını ayarlar. |
| [setMethod(int value)](#setMethod-int-) | Segmentasyon yöntemini ayarlar. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Varsayılan nokta ön‑hesaplama süreci ilerleme olay işleyicisini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Yeni bir [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) sınıfının örneğini başlatır.

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Arka plan nesne sayısı

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Otomatik maskeleme argümanlarını ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Görüntü. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Varsayılan darbeleri doldur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Görüntü. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Segmentasyon algoritması için argümanları alır.

Değer: Segmentasyon algoritması için argümanlar.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Tahmin edilen nesneleri alır.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - varsayılan nesneler.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Arka plan değiştirme rengini alır.

Değer: Arka plan değiştirme rengi. Bu renk, oluşturulan görüntülerde arka plan rengi olarak kullanılacaktır.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri alır.

**Returns:**
boolean - varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değer.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Birleştirilmiş nesneler dikdörtgenini alır.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır.

Değer:  true  ise ayrıştır; aksi takdirde,  false .

**Returns:**
boolean - her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değer.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Varsayılan arka plan darbelerini alır.

**Returns:**
com.aspose.psd.Point[] - varsayılan arka plan darbeleri.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Önceden hesaplanmış varsayılan ön plan darbelerini alır.

**Returns:**
com.aspose.psd.Point[] - önceden hesaplanmış varsayılan ön plan darbeleri.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Varsayılan nesne dikdörtgenlerini alır.

**Returns:**
com.aspose.psd.Rectangle[] - varsayılan nesne dikdörtgenleri.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Görüntü dışa aktarma seçeneklerini alır.

Değer: Oluşturulan görüntüleri üretmek için kullanılacak görüntü dışa aktarma seçenekleri.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Tüylenme yarıçapını alır.

**Returns:**
int - yumuşatma yarıçapı.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Maskeleme alanını alır.

Değer: Kaynak görüntünün bir kısmı olan maskeleme alanı. Rectangle.Empty değeri, tam kaynak görüntü alanını ifade eder.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Segmentasyon yöntemini alır.

Değer: Segmentasyon yöntemi.

**Returns:**
int - segmentasyon yöntemi.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini alır.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Tahmin edilen nesneler koleksiyonunun insan nesneleri içerip içermediğini gösteren bir değeri alır.

**Returns:**
boolean - koleksiyonda varsayılan nesnelerin insan nesneleri içerip içermediğini gösteren bir değer.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Segmentasyon algoritması için argümanları ayarlar.

Değer: Segmentasyon algoritması için argümanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | segmentasyon algoritması için argümanlar. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Tahmin edilen nesneleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | varsayılan nesneler. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Arka plan değiştirme rengini ayarlar.

Değer: Arka plan değiştirme rengi. Bu renk, oluşturulan görüntülerde arka plan rengi olarak kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | arka plan değiştirme rengi. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değer. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Birleştirilmiş nesneler dikdörtgeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | birleştirilmiş nesne dikdörtgeni. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri ayarlar.

Değer:  true  ise ayrıştır; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Maske içindeki her Şekli ayrı nesne olarak ya da birleştirilmiş nesne olarak arka plandan ayrılmış şekilde ayırmanın gereksiz olup olmadığını gösteren bir değer. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Varsayılan arka plan darbeleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | varsayılan arka plan darbeleri. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Önceden hesaplanmış varsayılan ön plan darbeleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | önceden hesaplanmış varsayılan ön plan darbeleri. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Varsayılan nesne dikdörtgenleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | varsayılan nesne dikdörtgenleri. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Görüntü dışa aktarma seçeneklerini ayarlar.

Değer: Oluşturulan görüntüleri üretmek için kullanılacak görüntü dışa aktarma seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | görüntü dışa aktarma seçenekleri. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Tüylenme yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yumuşatma yarıçapı. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Koleksiyonda varsayılan nesnelerin insan nesneleri içerip içermediğini gösteren bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | koleksiyonda varsayılan nesnelerin insan nesneleri içerip içermediğini gösteren bir değer. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Maskeleme alanını ayarlar.

Değer: Kaynak görüntünün bir kısmı olan maskeleme alanı. Rectangle.Empty değeri, tam kaynak görüntü alanını ifade eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | maskeleme alanı. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Segmentasyon yöntemini ayarlar.

Değer: Segmentasyon yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | segmentasyon yöntemi. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Varsayılan nokta ön‑hesaplama süreci ilerleme olay işleyicisini ayarlar.

Değer: İlerleme olayı işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | varsayılan nokta ön‑hesaplama süreci ilerleme olay işleyicisi. |

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

