---
title: "StrokeEffect"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Efek stroke Adobe Photoshop untuk lapisan PSD."
type: docs
weight: 17
url: /id/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Efek stroke Adobe® Photoshop® untuk lapisan PSD.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode blend. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Mendapatkan entitas |
| [getEffectType()](#getEffectType--) | Mendapatkan tipe efek. |
| [getFillSettings()](#getFillSettings--) | Mendapatkan atau mengatur pengaturan isi. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opacity. |
| [getOverprint()](#getOverprint--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) akan menggabungkan stroke dengan konten lapisan saat ini. |
| [getPosition()](#getPosition--) | Mendapatkan atau mengatur posisi efek stroke untuk mengontrol penyelarasan stroke Anda dengan konten lapisan PSD. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur lebar efek stroke. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode blend. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Mendapatkan atau mengatur pengaturan isi. |
| [setOpacity(byte value)](#setOpacity-byte-) | Mendapatkan atau mengatur opacity. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) akan menggabungkan stroke dengan konten lapisan saat ini. |
| [setPosition(short value)](#setPosition-short-) | Mendapatkan atau mengatur posisi efek stroke untuk mengontrol penyelarasan stroke Anda dengan konten lapisan PSD. |
| [setSize(int value)](#setSize-int-) | Mendapatkan atau mengatur lebar efek stroke. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


Mendapatkan tipe efek.

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Mendapatkan atau mengatur pengaturan isi.

Nilai: Pengaturan isi.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Mendapatkan atau mengatur opacity.

Nilai: Opacity.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) akan menggabungkan stroke dengan konten lapisan saat ini.

Nilai:  true  jika harus menggabungkan stroke dengan konten lapisan saat ini; selainnya,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Mendapatkan atau mengatur posisi efek stroke untuk mengontrol penyelarasan stroke Anda dengan konten lapisan PSD. Nilai dapat berupa [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) untuk menggambar stroke di dalam konten lapisan PSD, atau [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) untuk menggambar stroke di sekitar konten lapisan PSD, dan [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) untuk menggambar stroke baik di dalam maupun di luar.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Mendapatkan atau mengatur lebar efek stroke.

Nilai: Lebar efek stroke.

**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Mendapatkan atau mengatur pengaturan isi.

Nilai: Pengaturan isi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) akan menggabungkan stroke dengan konten lapisan saat ini.

Nilai:  true  jika harus menggabungkan stroke dengan konten lapisan saat ini; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Mendapatkan atau mengatur posisi efek stroke untuk mengontrol penyelarasan stroke Anda dengan konten lapisan PSD. Nilai dapat berupa [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) untuk menggambar stroke di dalam konten lapisan PSD, atau [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) untuk menggambar stroke di sekitar konten lapisan PSD, dan [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) untuk menggambar stroke baik di dalam maupun di luar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Mendapatkan atau mengatur lebar efek stroke.

Nilai: Lebar efek stroke.

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

