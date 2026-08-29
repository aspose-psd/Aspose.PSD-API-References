---
title: "GradientHelper"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas pembantu yang mengimplementasikan konversi data untuk properti gradien."
type: docs
weight: 34
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Kelas pembantu yang mengimplementasikan konversi data untuk properti gradien.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Konstanta integer model warna HSBL untuk gradien Noise. |
| [IntModelLAB](#IntModelLAB) | Konstanta integer model warna LBCL untuk gradien Noise. |
| [IntModelRGB](#IntModelRGB) | Konstanta integer model warna RGBC untuk gradien Noise. |
| [StrGradientNoise](#StrGradientNoise) | Konstanta string gradien Noise. |
| [StrGradientSolid](#StrGradientSolid) | Konstanta string gradien Solid. |
| [StrModelHSB](#StrModelHSB) | Konstanta string model warna HSBL untuk gradien Noise. |
| [StrModelLAB](#StrModelLAB) | Konstanta string model warna LBCL untuk gradien Noise. |
| [StrModelRGB](#StrModelRGB) | Konstanta string model warna RGBC untuk gradien Noise. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Konversi nilai GradientKind ke string. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Mengonversi nilai integer model warna noise ke NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Mengonversi instance NoiseColorModel ke nilai integer model warna noise. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Konversi nilai NoiseColorModel ke string. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Konversi nilai string ke GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Konversi nilai string ke NoiseColorModel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


Konstanta integer model warna HSBL untuk gradien Noise.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Konstanta integer model warna LBCL untuk gradien Noise.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Konstanta integer model warna RGBC untuk gradien Noise.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Konstanta string gradien Noise.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Konstanta string gradien Solid.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Konstanta string model warna HSBL untuk gradien Noise.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Konstanta string model warna LBCL untuk gradien Noise.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Konstanta string model warna RGBC untuk gradien Noise.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


Konversi nilai GradientKind ke string.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gradientKind | int | Nilai GradientKind. |

**Returns:**
java.lang.String - nilai string.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


Mengonversi nilai integer model warna noise ke NoiseColorModel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorModel | short | Nilai integer dari model warna noise. |

**Returns:**
short - instance NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Mengonversi instance NoiseColorModel ke nilai integer model warna noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorModel | short | Instance NoiseColorModel. |

**Returns:**
short - Nilai integer dari model warna gradien Noise.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Konversi nilai NoiseColorModel ke string.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorModel | short | Nilai NoiseColorModel. |

**Returns:**
java.lang.String - Nilai string dari model warna.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


Konversi nilai string ke GradientKind.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | java.lang.String | nilai string. |

**Returns:**
int - nilai GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Konversi nilai string ke NoiseColorModel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorModel | java.lang.String | nilai string. |

**Returns:**
short - nilai NoiseColorModel.
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

