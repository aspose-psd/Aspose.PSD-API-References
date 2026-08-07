---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Manajer untuk Lapisan Penyesuaian Kurva yang memanipulasi kurva"
type: docs
weight: 24
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Manajer untuk Lapisan Penyesuaian Kurva yang memanipulasi kurva
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Menginisialisasi instance baru dari kelas [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Menambahkan titik kurva. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Mendapatkan byte untuk sumber daya. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Mendapatkan titik kurva berdasarkan indeks. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Mendapatkan jumlah titik kurva. |
| [getMap_internalized()](#getMap-internalized--) | Mendapatkan peta untuk filter pemrosesan. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Mendapatkan jumlah saluran maksimum. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Memuat data dari byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Menghapus titik kurva. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Memperbarui titik kurva. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Menginisialisasi instance baru dari kelas [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxChannelCount | int | Jumlah saluran maksimum. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Menambahkan titik kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| x | byte | Lokasi x. |
| y | byte | Lokasi y. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Mendapatkan byte untuk sumber daya.

**Returns:**
byte[] - Byte untuk menyusun CurvResource
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Mendapatkan titik kurva berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| pointIndex | int | Indeks titik. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Mendapatkan jumlah titik kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |

**Returns:**
int - Jumlah Titik Kurva dalam saluran
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Mendapatkan peta untuk filter pemrosesan.

**Returns:**
byte[][] - Peta untuk pemrosesan saluran.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Mendapatkan jumlah saluran maksimum.

Nilai: Jumlah saluran maksimum.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Memuat data dari byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| byte | byte[] | Byte-byte. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Menghapus titik kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| pointIndex | int | Indeks titik. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Memperbarui titik kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| pointIndex | int | Indeks titik. |
| x | byte | Lokasi x. |
| y | byte | Lokasi y. |

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

