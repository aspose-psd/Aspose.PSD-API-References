---
title: "GaussWienerFilterOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "Gauss Wiener Filtre Seçenekleri Bulanıklığı Gider gauss"
type: docs
weight: 15
url: /tr/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss Wiener Filtre Seçenekleri Bulanıklığı Gider gauss
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | GaussWienerFilterOptions sınıfının yeni bir örneğini başlatır. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | GaussWienerFilterOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Parlaklığı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Bu [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getRadius()](#getRadius--) | Yarıçapı alır veya ayarlar. |
| [getSmooth()](#getSmooth--) | smooth değerini alır veya ayarlar. |
| [getSnr()](#getSnr--) | SNR (signal-to-noise ratio) değerini alır veya ayarlar, önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Bu örneğin kısmen yüklendiğini gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Parlaklığı alır veya ayarlar. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Bu [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Bu örneğin kısmen yüklendiğini gösteren bir değeri alır. |
| [setRadius(int value)](#setRadius-int-) | Yarıçapı alır veya ayarlar. |
| [setSmooth(double value)](#setSmooth-double-) | smooth değerini alır veya ayarlar. |
| [setSnr(double value)](#setSnr-double-) | SNR (signal-to-noise ratio) değerini alır veya ayarlar, önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


GaussWienerFilterOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | int | Yarıçap. |
| smooth | double | Yumuşaklık. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


GaussWienerFilterOptions sınıfının yeni bir örneğini başlatır. Varsayılan ayarlarla.

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5, varsayılan değer = 1.15

Değer: Parlaklık.

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


Bu [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. Gri tonlama modu veya RGB modu döndürür.

Değer:  true  eğer gri tonlamalıysa; aksi takdirde false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


Yarıçapı alır veya ayarlar.

Değer: Yarıçap.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


smooth değerini alır veya ayarlar.

Değer: Yumuşaklık.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


SNR (signal-to-noise ratio) değerini alır veya ayarlar, önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007

Değer: SNR.

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


Bu örneğin kısmen yüklendiğini gösteren bir değeri alır.

Değer:  true  eğer bu örnek kısmen yüklendiyse; aksi takdirde,  false .

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


Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5, varsayılan değer = 1.15

Değer: Parlaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Bu [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. Gri tonlama modu veya RGB modu döndürür.

Değer:  true  eğer gri tonlamalıysa; aksi takdirde false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Bu örneğin kısmen yüklendiğini gösteren bir değeri alır.

Değer:  true  eğer bu örnek kısmen yüklendiyse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Yarıçapı alır veya ayarlar.

Değer: Yarıçap.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


smooth değerini alır veya ayarlar.

Değer: Yumuşaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


SNR (signal-to-noise ratio) değerini alır veya ayarlar, önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007

Değer: SNR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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

