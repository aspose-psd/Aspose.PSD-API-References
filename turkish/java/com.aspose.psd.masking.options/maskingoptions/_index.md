---
title: "MaskingOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "Ortak görüntü maskeleme seçeneklerini temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Ortak görüntü maskeleme seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Arka plan nesne sayısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Segmentasyon algoritması için argümanları alır. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Arka plan değiştirme rengini alır. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır. |
| [getExportOptions()](#getExportOptions--) | Görüntü dışa aktarma seçeneklerini alır. |
| [getMaskingArea()](#getMaskingArea--) | Maskeleme alanını alır. |
| [getMethod()](#getMethod--) | Segmentasyon yöntemini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Segmentasyon algoritması için argümanları ayarlar. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Arka plan değiştirme rengini ayarlar. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri ayarlar. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Görüntü dışa aktarma seçeneklerini ayarlar. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Maskeleme alanını ayarlar. |
| [setMethod(int value)](#setMethod-int-) | Segmentasyon yöntemini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Arka plan nesne sayısı

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Segmentasyon algoritması için argümanları alır.

Değer: Segmentasyon algoritması için argümanlar.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Arka plan değiştirme rengini alır.

Değer: Arka plan değiştirme rengi. Bu renk, oluşturulan görüntülerde arka plan rengi olarak kullanılacaktır.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır.

Değer:  true  ise ayrıştır; aksi takdirde,  false .

**Returns:**
boolean - her bir Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değer.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Görüntü dışa aktarma seçeneklerini alır.

Değer: Oluşturulan görüntüleri üretmek için kullanılacak görüntü dışa aktarma seçenekleri.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
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

