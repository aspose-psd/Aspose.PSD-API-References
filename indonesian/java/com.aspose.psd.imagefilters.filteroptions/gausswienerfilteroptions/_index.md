---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi Filter Gauss Wiener Deblur gauss"
type: docs
weight: 15
url: /id/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Opsi Filter Gauss Wiener Deblur gauss
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Menginisialisasi sebuah instance baru dari kelas  GaussWienerFilterOptions  . |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Menginisialisasi sebuah instance baru dari kelas  GaussWienerFilterOptions  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Mendapatkan atau mengatur brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) bergrayscale. |
| [getRadius()](#getRadius--) | Mendapatkan atau mengatur radius. |
| [getSmooth()](#getSmooth--) | Mendapatkan atau mengatur kehalusan. |
| [getSnr()](#getSnr--) | Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Mendapatkan atau mengatur brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) bergrayscale. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Mendapatkan nilai yang menunjukkan apakah instance ini dimuat secara parsial. |
| [setRadius(int value)](#setRadius-int-) | Mendapatkan atau mengatur radius. |
| [setSmooth(double value)](#setSmooth-double-) | Mendapatkan atau mengatur kehalusan. |
| [setSnr(double value)](#setSnr-double-) | Mendapatkan atau mengatur SNR (signal-to-noise ratio) rentang yang direkomendasikan 0.002 - 0.009, nilai default = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Menginisialisasi sebuah instance baru dari kelas  GaussWienerFilterOptions  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | int | Radius. |
| halus | double | Halus. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Menginisialisasi sebuah instance baru dari kelas  GaussWienerFilterOptions  . Dengan pengaturan default.

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
### getRadius() {#getRadius--}
```
public int getRadius()
```


Mendapatkan atau mengatur radius.

Nilai: Radius.

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

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Mendapatkan atau mengatur radius.

Nilai: Radius.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

