---
title: "MotionWienerFilterOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi filter dekonvolusi     menghilangkan blur gerakan"
type: docs
weight: 18
url: /id/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Opsi filter dekonvolusi deblur motion
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Menginisialisasi sebuah instance baru dari kelas  MotionWienerFilterOptions  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Mendapatkan atau mengatur sudut dalam gradus. |
| [getBrightness()](#getBrightness--) | Mendapatkan atau mengatur brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) bergrayscale. |
| [getLength()](#getLength--) | Mendapatkan atau mengatur panjang. |
| [getSmooth()](#getSmooth--) | Mendapatkan atau mengatur kehalusan. |
| [getSnr()](#getSnr--) | Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Mendapatkan atau mengatur sudut dalam gradus. |
| [setBrightness(double value)](#setBrightness-double-) | Mendapatkan atau mengatur brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) bergrayscale. |
| [setLength(int value)](#setLength-int-) | Mendapatkan atau mengatur panjang. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial. |
| [setSmooth(double value)](#setSmooth-double-) | Mendapatkan atau mengatur kehalusan. |
| [setSnr(double value)](#setSnr-double-) | Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Menginisialisasi sebuah instance baru dari kelas  MotionWienerFilterOptions  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| panjang | int | Panjang. |
| halus | double | Halus. |
| angle | double | Sudut dalam gradus. |

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
public double getAngle()
```


Mendapatkan atau mengatur sudut dalam gradus.

Nilai: Sudut.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Mendapatkan atau mengatur kecerahan. rentang yang direkomendasikan 1 - 1.5 nilai default = 1.15

Nilai: brightness.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ini bergrayscale. Mengembalikan mode grayscale atau mode RGB.

Nilai:  true  jika grayscale; jika tidak,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Mendapatkan atau mengatur panjang.

Nilai: Panjang.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Mendapatkan atau mengatur kehalusan.

Nilai: Halus.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007

Nilai: SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial.

Nilai:  true  jika instance ini dimuat sebagian; jika tidak,  false .

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Mendapatkan atau mengatur sudut dalam gradus.

Nilai: Sudut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Mendapatkan atau mengatur kecerahan. rentang yang direkomendasikan 1 - 1.5 nilai default = 1.15

Nilai: brightness.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ini bergrayscale. Mengembalikan mode grayscale atau mode RGB.

Nilai:  true  jika grayscale; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Mendapatkan atau mengatur panjang.

Nilai: Panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial.

Nilai:  true  jika instance ini dimuat sebagian; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Mendapatkan atau mengatur kehalusan.

Nilai: Halus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007

Nilai: SNR.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

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

