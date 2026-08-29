---
title: "GradientHelper"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "فئة المساعدة التي تنفّذ تحويل البيانات لخصائص التدرج."
type: docs
weight: 34
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

فئة المساعدة التي تنفّذ تحويل البيانات لخصائص التدرج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | ثابت عدد صحيح لنموذج اللون HSBL لتدرج الضوضاء. |
| [IntModelLAB](#IntModelLAB) | ثابت عدد صحيح لنموذج اللون LBCL لتدرج الضوضاء. |
| [IntModelRGB](#IntModelRGB) | ثابت عدد صحيح لنموذج اللون RGBC لتدرج الضوضاء. |
| [StrGradientNoise](#StrGradientNoise) | ثابت سلسلة تدرج الضوضاء. |
| [StrGradientSolid](#StrGradientSolid) | ثابت سلسلة التدرج الصلب. |
| [StrModelHSB](#StrModelHSB) | ثابت سلسلة نموذج اللون HSBL لتدرج الضوضاء. |
| [StrModelLAB](#StrModelLAB) | ثابت سلسلة نموذج اللون LBCL لتدرج الضوضاء. |
| [StrModelRGB](#StrModelRGB) | ثابت سلسلة نموذج اللون RGBC لتدرج الضوضاء. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | تحويل قيمة GradientKind إلى سلسلة. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | يحوّل القيمة العددية لنموذج لون الضوضاء إلى NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | يحوّل كائن NoiseColorModel إلى قيمة عددية لنموذج لون الضوضاء. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | تحويل قيمة NoiseColorModel إلى سلسلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | تحويل قيمة السلسلة إلى GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | تحويل قيمة السلسلة إلى NoiseColorModel. |
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


ثابت عدد صحيح لنموذج اللون HSBL لتدرج الضوضاء.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


ثابت عدد صحيح لنموذج اللون LBCL لتدرج الضوضاء.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


ثابت عدد صحيح لنموذج اللون RGBC لتدرج الضوضاء.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


ثابت سلسلة تدرج الضوضاء.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


ثابت سلسلة التدرج الصلب.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


ثابت سلسلة نموذج اللون HSBL لتدرج الضوضاء.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


ثابت سلسلة نموذج اللون LBCL لتدرج الضوضاء.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


ثابت سلسلة نموذج اللون RGBC لتدرج الضوضاء.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


تحويل قيمة GradientKind إلى سلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gradientKind | int | قيمة GradientKind. |

**Returns:**
java.lang.String - قيمة السلسلة.
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


يحوّل القيمة العددية لنموذج لون الضوضاء إلى NoiseColorModel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorModel | short | القيمة العددية لنموذج لون الضوضاء. |

**Returns:**
short - كائن NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


يحوّل كائن NoiseColorModel إلى قيمة عددية لنموذج لون الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorModel | short | كائن NoiseColorModel. |

**Returns:**
short - قيمة عددية من نوع Integer لنموذج لون تدرج الضوضاء.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


تحويل قيمة NoiseColorModel إلى سلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorModel | short | قيمة NoiseColorModel. |

**Returns:**
java.lang.String - قيمة سلسلة لنموذج اللون.
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


تحويل قيمة السلسلة إلى GradientKind.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| str | java.lang.String | قيمة سلسلة. |

**Returns:**
int - قيمة GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


تحويل قيمة السلسلة إلى NoiseColorModel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorModel | java.lang.String | قيمة سلسلة. |

**Returns:**
short - قيمة NoiseColorModel.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

