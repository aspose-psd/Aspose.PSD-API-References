---
title: "DropShadowEffect"
second_title: "Java için Aspose.PSD API Referansı"
description: "Düşen Gölge Katman etkisi"
type: docs
weight: 12
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Düşen Gölge Katman etkisi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Açıyı derece cinsinden alır veya ayarlar. |
| [getBlendMode()](#getBlendMode--) | Karışım modunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Rengi alır veya ayarlar. |
| [getDistance()](#getDistance--) | Mesafeyi piksel cinsinden alır veya ayarlar. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Varlığı alır |
| [getEffectType()](#getEffectType--) | Bir efekt türünü alır |
| [getKnocksOut()](#getKnocksOut--) | Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out]. |
| [getNoise()](#getNoise--) | Gürültüyü alır veya ayarlar. |
| [getOpacity()](#getOpacity--) | Opaklığı alır veya ayarlar. |
| [getSize()](#getSize--) | Bulanıklık değerini piksel cinsinden alır veya ayarlar. |
| [getSpread()](#getSpread--) | Yoğunluğu yüzde olarak alır veya ayarlar. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Bu açının tüm katman efektlerinde kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. [use this angle in all of the layer effects] |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Belirli indeksteki katman etkisini kaldırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Açıyı derece cinsinden alır veya ayarlar. |
| [setBlendMode(long value)](#setBlendMode-long-) | Karışım modunu alır veya ayarlar. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Rengi alır veya ayarlar. |
| [setDistance(int value)](#setDistance-int-) | Mesafeyi piksel cinsinden alır veya ayarlar. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Gürültüyü alır veya ayarlar. |
| [setOpacity(byte value)](#setOpacity-byte-) | Opaklığı alır veya ayarlar. |
| [setSize(int value)](#setSize-int-) | Bulanıklık değerini piksel cinsinden alır veya ayarlar. |
| [setSpread(int value)](#setSpread-int-) | Yoğunluğu yüzde olarak alır veya ayarlar. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Bu açının tüm katman efektlerinde kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. [use this angle in all of the layer effects] |
| [setVisible(boolean value)](#setVisible-boolean-) | Belirli indeksteki katman etkisini kaldırır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Açıyı derece cinsinden alır veya ayarlar.

Değer: Açı.

**Returns:**
int
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Rengi alır veya ayarlar.

Değer: Renk.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Mesafeyi piksel cinsinden alır veya ayarlar.

Değer: Mesafe.

**Returns:**
int
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Katman piksel sınırları. |
| globalAngle | int | Genel ışık açısını hesaplamak için genel açı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Varlığı alır

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Bir efekt türünü alır

**Returns:**
int
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out].

Değer:  true  eğer [knocks out]; aksi takdirde,  false .

**Returns:**
boolean
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Gürültüyü alır veya ayarlar.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Opaklığı alır veya ayarlar.

Değer: Opaklık.

**Returns:**
byte
### getSize() {#getSize--}
```
public final int getSize()
```


Bulanıklık değerini piksel cinsinden alır veya ayarlar.

Değer: Boyut.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Yoğunluğu yüzde olarak alır veya ayarlar.

Değer: Yayılım.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Bu açının tüm katman efektlerinde kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. [use this angle in all of the layer effects]

Değer:  true  eğer [use global light]; aksi takdirde,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


Açıyı derece cinsinden alır veya ayarlar.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Karışım modunu alır veya ayarlar.

Değer: Karışım modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Rengi alır veya ayarlar.

Değer: Renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Mesafeyi piksel cinsinden alır veya ayarlar.

Değer: Mesafe.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out].

Değer:  true  eğer [knocks out]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Gürültüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Opaklığı alır veya ayarlar.

Değer: Opaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Bulanıklık değerini piksel cinsinden alır veya ayarlar.

Değer: Boyut.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Yoğunluğu yüzde olarak alır veya ayarlar.

Değer: Yayılım.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Bu açının tüm katman efektlerinde kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. [use this angle in all of the layer effects]

Değer:  true  eğer [use global light]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Belirli indeksteki katman etkisini kaldırır.

Value:  true  eğer bu örnek görünürse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

