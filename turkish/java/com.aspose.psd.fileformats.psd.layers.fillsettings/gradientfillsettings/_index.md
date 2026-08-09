---
title: "GradientFillSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Degrade doldurma efekt ayarları."
type: docs
weight: 14
url: /tr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Degrade doldurma efekt ayarları.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Yeni bir [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAngle()](#getAngle--) | Açıyı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Gradyanın konumunu doğru hesaplamak için katman kapsayıcısının sınırlarını alır veya ayarlar. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Mevcut Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) değerine karşılık gelen **denormalized** gradyan ölçeğini (UI Scale) hesaplar ve döndürür. |
| [getDither()](#getDither--) | Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getFillType()](#getFillType--) | Dolgu türü. |
| [getGradient()](#getGradient--) | Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Gradyanın türünü alır veya ayarlar. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [getReverse()](#getReverse--) | Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ters olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getScale()](#getScale--) | **normalized** gradyan ölçeğini (yüzde olarak) alır veya ayarlar. |
| [getVerticalOffset()](#getVerticalOffset--) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Değer değiştiğinde tetikler. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Açıyı alır veya ayarlar. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Gradyanın konumunu doğru hesaplamak için katman kapsayıcısının sınırlarını alır veya ayarlar. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Belirtilen denormalized ölçek (UI) değerini **normalized** eşdeğerine dönüştürür ve Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) değerine atar. |
| [setDither(boolean value)](#setDither-boolean-) | Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Gradyanın türünü alır veya ayarlar. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [setReverse(boolean value)](#setReverse-boolean-) | Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ters olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setScale(int value)](#setScale-int-) | **normalized** gradyan ölçeğini (yüzde olarak) alır veya ayarlar. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Yeni bir [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) sınıfının örneğini başlatır.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Açıyı alır veya ayarlar.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Gradyanın konumunu doğru hesaplamak için katman kapsayıcısının sınırlarını alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Mevcut Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) değerine karşılık gelen **denormalized** gradyan ölçeğini (UI Scale) hesaplar ve döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Gradyanın sınırları. |

**Returns:**
int - Photoshop'ta görüntülendiği gibi yüzde olarak gösterilen denormalize (UI) ölçeği.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Dolgu türü.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Yüzde olarak yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ters olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


**normalized** gradyan ölçeğini (yüzde olarak) alır veya ayarlar.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Yüzde olarak dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Değer değiştiğinde tetikler.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Açıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Gradyanın konumunu doğru hesaplamak için katman kapsayıcısının sınırlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Belirtilen denormalize ölçek (UI) ölçek değerini **normalized** eşdeğerine dönüştürür ve Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) özelliğine atar. Dönüştürme, gradient\\u2019s mevcut Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) ve sağlanan fillArea'yi kullanarak normalizasyon faktörünü hesaplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Denormalize ölçek, Photoshop tarafından görüntülendiği gibi yüzde olarak UI Ölçeği; |
| fillArea | [Size](../../com.aspose.psd/size) | Gradyanın sınırları. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Belirli gradient tanım örneğini alır veya ayarlar (Solid/Noise).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Gradyanın türünü alır veya ayarlar.

Değer: Gradyanın türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Yüzde olarak yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Bu [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ters olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


**normalized** gradyan ölçeğini (yüzde olarak) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Yüzde olarak dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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

