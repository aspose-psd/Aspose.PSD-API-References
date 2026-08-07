---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Manajer untuk Curves Adjustment Layer yang memanipulasi peta piksel"
type: docs
weight: 25
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Manajer untuk Lapisan Penyesuaian Kurva yang memanipulasi peta piksel
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Menginisialisasi instance baru dari kelas [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Mendapatkan byte untuk sumber daya. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Mendapatkan peta untuk filter pemrosesan |
| [getMaxChannelCount()](#getMaxChannelCount--) | Mendapatkan jumlah saluran maksimum. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Mendapatkan nilai pada posisi. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Memuat data dari byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Mengatur ke nilai default pada posisi. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Mengatur nilai pada posisi. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Mengatur nilai seluruh kanal. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Menginisialisasi instance baru dari kelas [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxChannelCount | int | Jumlah saluran maksimum. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Mendapatkan peta untuk filter pemrosesan

**Returns:**
byte[][] - peta Transformasi
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Mendapatkan jumlah saluran maksimum.

Nilai: Jumlah saluran maksimum.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Mendapatkan nilai pada posisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| position | byte | Posisi. |

**Returns:**
byte - Nilai kurva berdasarkan posisinya
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Mengatur ke nilai default pada posisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| position | byte | Posisi. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Mengatur nilai pada posisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| position | byte | Posisi. |
| nilai | byte | Nilai. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Mengatur nilai seluruh kanal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |
| channelValue | byte[] | Nilai kanal. |

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

