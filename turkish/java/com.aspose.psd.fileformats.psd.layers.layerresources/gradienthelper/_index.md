---
title: "GradientHelper"
second_title: "Java için Aspose.PSD API Referansı"
description: "Gradyan özellikleri için veri dönüşümünü uygulayan yardımcı sınıf"
type: docs
weight: 34
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Gradyan özellikleri için veri dönüşümünü uygulayan yardımcı sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Gürültü gradyanı için HSBL renk modeli tamsayı sabiti. |
| [IntModelLAB](#IntModelLAB) | Gürültü gradyanı için LBCL renk modeli tamsayı sabiti. |
| [IntModelRGB](#IntModelRGB) | Gürültü gradyanı için RGBC renk modeli tamsayı sabiti. |
| [StrGradientNoise](#StrGradientNoise) | Gürültü gradyan dize sabiti. |
| [StrGradientSolid](#StrGradientSolid) | Katı gradyan dize sabiti. |
| [StrModelHSB](#StrModelHSB) | Gürültü gradyanı için HSBL renk modeli dize sabiti. |
| [StrModelLAB](#StrModelLAB) | Gürültü gradyanı için LBCL renk modeli dize sabiti. |
| [StrModelRGB](#StrModelRGB) | Gürültü gradyanı için RGBC renk modeli dize sabiti. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | GradientKind değerini dizeye dönüştür. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Gürültü renk modelinin tamsayı değerini NoiseColorModel'e dönüştürür. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | NoiseColorModel örneğini gürültü renk modelinin tamsayı değerine dönüştürür. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | NoiseColorModel değerini dizeye dönüştür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Dize değerini GradientKind'e dönüştür. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Dize değerini NoiseColorModel'e dönüştür. |
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


Gürültü gradyanı için HSBL renk modeli tamsayı sabiti.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Gürültü gradyanı için LBCL renk modeli tamsayı sabiti.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Gürültü gradyanı için RGBC renk modeli tamsayı sabiti.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Gürültü gradyan dize sabiti.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Katı gradyan dize sabiti.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Gürültü gradyanı için HSBL renk modeli dize sabiti.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Gürültü gradyanı için LBCL renk modeli dize sabiti.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Gürültü gradyanı için RGBC renk modeli dize sabiti.

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


GradientKind değerini dizeye dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gradientKind | int | GradientKind değeri. |

**Returns:**
java.lang.String - dize değeri.
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


Gürültü renk modelinin tamsayı değerini NoiseColorModel'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorModel | short | Gürültü renk modelinin tamsayı değeri. |

**Returns:**
short - NoiseColorModel örneği.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


NoiseColorModel örneğini gürültü renk modelinin tamsayı değerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorModel | short | NoiseColorModel örneği. |

**Returns:**
short - Noise gradyan renk modelinin tam sayı değeri.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


NoiseColorModel değerini dizeye dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorModel | short | NoiseColorModel değeri. |

**Returns:**
java.lang.String - renk modelinin dize değeri.
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


Dize değerini GradientKind'e dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | dize değeri. |

**Returns:**
int - GradientKind değeri.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Dize değerini NoiseColorModel'e dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorModel | java.lang.String | dize değeri. |

**Returns:**
short - NoiseColorModel değeri.
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

