---
title: "DropShadowEffect"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Efek lapisan Drop Shadow"
type: docs
weight: 12
url: /id/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Efek lapisan Drop Shadow
## Metode

| Metode | Deskripsi |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Mendapatkan atau mengatur sudut dalam derajat. |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode blend. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna. |
| [getDistance()](#getDistance--) | Mendapatkan atau mengatur jarak dalam piksel. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Mendapatkan entitas |
| [getEffectType()](#getEffectType--) | Mendapatkan tipe efek. |
| [getKnocksOut()](#getKnocksOut--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out]. |
| [getNoise()](#getNoise--) | Mendapatkan atau mengatur noise. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opacity. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur nilai blur dalam piksel. |
| [getSpread()](#getSpread--) | Mendapatkan atau mengatur intensitas sebagai persentase. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Mendapatkan atau mengatur sudut dalam derajat. |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode blend. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna. |
| [setDistance(int value)](#setDistance-int-) | Mendapatkan atau mengatur jarak dalam piksel. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Mendapatkan atau mengatur noise. |
| [setOpacity(byte value)](#setOpacity-byte-) | Mendapatkan atau mengatur opacity. |
| [setSize(int value)](#setSize-int-) | Mendapatkan atau mengatur nilai blur dalam piksel. |
| [setSpread(int value)](#setSpread-int-) | Mendapatkan atau mengatur intensitas sebagai persentase. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Mendapatkan atau mengatur sudut dalam derajat.

Nilai: Sudut.

**Returns:**
int
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
### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Mendapatkan atau mengatur jarak dalam piksel.

Nilai: Jarak.

**Returns:**
int
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


Mendapatkan tipe efek.

**Returns:**
int
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out].

Nilai:  true  jika [knocks out]; selainnya,  false .

**Returns:**
boolean
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
### getSize() {#getSize--}
```
public final int getSize()
```


Mendapatkan atau mengatur nilai blur dalam piksel.

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
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan].

Nilai: true jika [use global light]; selain itu, false.

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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


Mendapatkan atau mengatur sudut dalam derajat.

Nilai: Sudut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Mendapatkan atau mengatur jarak dalam piksel.

Nilai: Jarak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out].

Nilai:  true  jika [knocks out]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Mendapatkan atau mengatur nilai blur dalam piksel.

Nilai: Ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan].

Nilai: true jika [use global light]; selain itu, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

