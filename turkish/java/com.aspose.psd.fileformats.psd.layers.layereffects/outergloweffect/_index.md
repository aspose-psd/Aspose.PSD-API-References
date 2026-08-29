---
title: "OuterGlowEffect"
second_title: "Java için Aspose.PSD API Referansı"
description: "Dış Parıltı Katman etkisi"
type: docs
weight: 15
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Dış Parıltı Katman etkisi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Karışım modunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Giriş katman piksel sınırlarına dayanarak efekt piksellerinin sınırlarını hesaplar ve alır. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Varlığı alır |
| [getEffectType()](#getEffectType--) | Bir efekt türü alır. |
| [getFillColor()](#getFillColor--) | Rengi alır veya ayarlar. |
| [getIntensity()](#getIntensity--) | Açıyı derece cinsinden alır veya ayarlar. |
| [getJitter()](#getJitter--) | Gürültüyü alır veya ayarlar. |
| [getNoise()](#getNoise--) | Gürültüyü alır veya ayarlar. |
| [getOpacity()](#getOpacity--) | Opaklığı alır veya ayarlar. |
| [getRange()](#getRange--) | Gürültüyü alır veya ayarlar. |
| [getSize()](#getSize--) | Bulanıklık değerini piksel cinsinden alır. |
| [getSpread()](#getSpread--) | Yoğunluğu yüzde olarak alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Etkin AntiAliasing etkisini alır veya ayarlar |
| [isSoftBlend()](#isSoftBlend--) | Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out]. |
| [isVisible()](#isVisible--) | Belirli indeksteki katman etkisini kaldırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Etkin AntiAliasing etkisini alır veya ayarlar |
| [setBlendMode(long value)](#setBlendMode-long-) | Karışım modunu alır veya ayarlar. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Rengi alır veya ayarlar. |
| [setIntensity(int value)](#setIntensity-int-) | Açıyı derece cinsinden alır veya ayarlar. |
| [setJitter(int value)](#setJitter-int-) | Gürültüyü alır veya ayarlar. |
| [setNoise(int value)](#setNoise-int-) | Gürültüyü alır veya ayarlar. |
| [setOpacity(byte value)](#setOpacity-byte-) | Opaklığı alır veya ayarlar. |
| [setRange(int value)](#setRange-int-) | Gürültüyü alır veya ayarlar. |
| [setSize(int value)](#setSize-int-) | Bulanıklık değerini piksel cinsinden alır. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Yoğunluğu yüzde olarak alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Belirli indeksteki katman etkisini kaldırır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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


Bir efekt türü alır.

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Rengi alır veya ayarlar.

Değer: Renk.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Açıyı derece cinsinden alır veya ayarlar.

Değer: Açı.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Gürültüyü alır veya ayarlar.

**Returns:**
int
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
### getRange() {#getRange--}
```
public final int getRange()
```


Gürültüyü alır veya ayarlar.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Bulanıklık değerini piksel cinsinden alır.

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


Etkin AntiAliasing etkisini alır veya ayarlar

Değer: Mesafe.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out].

Değer:  true  eğer [knocks out]; aksi takdirde,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Etkin AntiAliasing etkisini alır veya ayarlar

Değer: Mesafe.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Rengi alır veya ayarlar.

Değer: Renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Açıyı derece cinsinden alır veya ayarlar.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Gürültüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Gürültüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Bulanıklık değerini piksel cinsinden alır.

Değer: Boyut.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Kapatıp kapatmadığını gösteren bir değeri alır veya ayarlar [knocks out].

Değer:  true  eğer [knocks out]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

