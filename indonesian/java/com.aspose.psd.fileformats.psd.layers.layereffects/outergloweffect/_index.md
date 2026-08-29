---
title: "OuterGlowEffect"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Efek lapisan Outer Glow"
type: docs
weight: 15
url: /id/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Efek lapisan Outer Glow
## Metode

| Metode | Deskripsi |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode blend. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Mendapatkan entitas |
| [getEffectType()](#getEffectType--) | Mendapatkan tipe efek |
| [getFillColor()](#getFillColor--) | Mendapatkan atau mengatur warna. |
| [getIntensity()](#getIntensity--) | Mendapatkan atau mengatur sudut dalam derajat. |
| [getJitter()](#getJitter--) | Mendapatkan atau mengatur noise. |
| [getNoise()](#getNoise--) | Mendapatkan atau mengatur noise. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opacity. |
| [getRange()](#getRange--) | Mendapatkan atau mengatur noise. |
| [getSize()](#getSize--) | Mendapatkan nilai blur dalam piksel. |
| [getSpread()](#getSpread--) | Mendapatkan atau mengatur intensitas sebagai persentase. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Mendapatkan atau mengatur efek AntiAliasing yang diaktifkan |
| [isSoftBlend()](#isSoftBlend--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out]. |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Mendapatkan atau mengatur efek AntiAliasing yang diaktifkan |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode blend. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Mendapatkan atau mengatur warna. |
| [setIntensity(int value)](#setIntensity-int-) | Mendapatkan atau mengatur sudut dalam derajat. |
| [setJitter(int value)](#setJitter-int-) | Mendapatkan atau mengatur noise. |
| [setNoise(int value)](#setNoise-int-) | Mendapatkan atau mengatur noise. |
| [setOpacity(byte value)](#setOpacity-byte-) | Mendapatkan atau mengatur opacity. |
| [setRange(int value)](#setRange-int-) | Mendapatkan atau mengatur noise. |
| [setSize(int value)](#setSize-int-) | Mendapatkan nilai blur dalam piksel. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Mendapatkan atau mengatur intensitas sebagai persentase. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Mendapatkan atau mengatur mode blend.

Nilai: Mode blend.

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


Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas piksel lapisan. |
| globalAngle | int | Sudut global untuk menghitung sudut cahaya global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Mendapatkan entitas

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Mendapatkan tipe efek

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Mendapatkan atau mengatur sudut dalam derajat.

Nilai: Sudut.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Mendapatkan atau mengatur noise.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Mendapatkan atau mengatur noise.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Mendapatkan atau mengatur opacity.

Nilai: Opacity.

**Returns:**
byte
### getRange() {#getRange--}
```
public final int getRange()
```


Mendapatkan atau mengatur noise.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Mendapatkan nilai blur dalam piksel.

Nilai: Ukuran.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Mendapatkan atau mengatur intensitas sebagai persentase.

Nilai: Penyebaran.

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


Mendapatkan atau mengatur efek AntiAliasing yang diaktifkan

Nilai: Jarak.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out].

Nilai:  true  jika [knocks out]; selainnya,  false .

**Returns:**
boolean
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

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


Mendapatkan atau mengatur efek AntiAliasing yang diaktifkan

Nilai: Jarak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Mendapatkan atau mengatur mode blend.

Nilai: Mode blend.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Mendapatkan atau mengatur sudut dalam derajat.

Nilai: Sudut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Mendapatkan atau mengatur noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Mendapatkan atau mengatur noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Mendapatkan atau mengatur opacity.

Nilai: Opacity.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Mendapatkan atau mengatur noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Mendapatkan nilai blur dalam piksel.

Nilai: Ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out].

Nilai:  true  jika [knocks out]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Mendapatkan atau mengatur intensitas sebagai persentase.

Nilai: Penyebaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

