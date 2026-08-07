---
title: "ILayerEffect"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Antarmuka untuk Efek Lapisan"
type: docs
weight: 20
url: /id/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Antarmuka untuk Efek Lapisan
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode blend. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input. |
| [getEffectType()](#getEffectType--) | Mendapatkan tipe efek. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opacity dimana 255 = 100%. |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode blend. |
| [setOpacity(byte value)](#setOpacity-byte-) | Mendapatkan atau mengatur opacity dimana 255 = 100%. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Mendapatkan atau mengatur mode blend.

Nilai: Mode blend.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas piksel lapisan. |
| globalAngle | int | Sudut global untuk menghitung sudut cahaya global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Mendapatkan tipe efek.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Mendapatkan atau mengatur opacity dimana 255 = 100%.

Nilai: Opacity.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Mendapatkan atau mengatur mode blend.

Nilai: Mode blend.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Mendapatkan atau mengatur opacity dimana 255 = 100%.

Nilai: Opacity.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

