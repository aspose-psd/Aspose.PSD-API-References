---
title: "BaseGradientFillSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Temel degrade tanım sınıfı."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Temel gradyan tanım sınıfı. Hem Katı hem de Gürültü gradyan türleri için ortak özellikler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Yeni bir [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) sınıfının örneğini başlatır. |
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
| [getDither()](#getDither--) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getFillType()](#getFillType--) | Dolgu türü. |
| [getGradientMode()](#getGradientMode--) | Bu gradyan için modu alır. |
| [getGradientName()](#getGradientName--) | Gradyanın adını alır veya ayarlar. |
| [getGradientType()](#getGradientType--) | Gradyanın türünü alır veya ayarlar. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [getReverse()](#getReverse--) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getScale()](#getScale--) | Ölçeği alır veya ayarlar. |
| [getVerticalOffset()](#getVerticalOffset--) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Değer değiştiğinde tetikler. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Açıyı alır veya ayarlar. |
| [setDither(boolean value)](#setDither-boolean-) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Bu gradyan için modu alır. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gradyanın adını alır veya ayarlar. |
| [setGradientType(int value)](#setGradientType-int-) | Gradyanın türünü alır veya ayarlar. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [setReverse(boolean value)](#setReverse-boolean-) | Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setScale(int value)](#setScale-int-) | Ölçeği alır veya ayarlar. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Yüzde olarak dikey ofseti alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Yeni bir [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) sınıfının örneğini başlatır.

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

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
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Bu gradyanın kipini alır. 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Returns:**
java.lang.String
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Ölçeği alır veya ayarlar.

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

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Bu gradyanın kipini alır. 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Bu [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Ölçeği alır veya ayarlar.

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

