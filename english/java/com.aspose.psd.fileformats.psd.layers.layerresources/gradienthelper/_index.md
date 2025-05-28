---
title: GradientHelper
second_title: Aspose.PSD for Java API Reference
description: Helper class that implement conversion of data for gradient properties.
type: docs
weight: 33
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Helper class that implement conversion of data for gradient properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Fields

| Field | Description |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL color model integer constant for Noise gradient. |
| [IntModelLAB](#IntModelLAB) | LBCL color model integer constant for Noise gradient. |
| [IntModelRGB](#IntModelRGB) | RGBC color model integer constant for Noise gradient. |
| [StrGradientNoise](#StrGradientNoise) | Noise gradient string constant. |
| [StrGradientSolid](#StrGradientSolid) | Solid gradient string constant. |
| [StrModelHSB](#StrModelHSB) | HSBL color model string constant for Noise gradient. |
| [StrModelLAB](#StrModelLAB) | LBCL color model string constant for Noise gradient. |
| [StrModelRGB](#StrModelRGB) | RGBC color model string constant for Noise gradient. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Convert GradientKind value to string. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Converts integer value of noise color model to NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Converts NoiseColorModel instance to integer value of noise color model. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Convert NoiseColorModel value to string. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Convert string value to GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Convert string value to NoiseColorModel. |
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


HSBL color model integer constant for Noise gradient.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL color model integer constant for Noise gradient.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC color model integer constant for Noise gradient.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Noise gradient string constant.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Solid gradient string constant.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


HSBL color model string constant for Noise gradient.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


LBCL color model string constant for Noise gradient.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


RGBC color model string constant for Noise gradient.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Convert GradientKind value to string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientKind | int | GradientKind value. |

**Returns:**
java.lang.String - string value.
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


Converts integer value of noise color model to NoiseColorModel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorModel | short | Integer value of noise color model. |

**Returns:**
short - NoiseColorModel instance.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Converts NoiseColorModel instance to integer value of noise color model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorModel | short | NoiseColorModel instance. |

**Returns:**
short - Integer value of Noise gradient color model.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Convert NoiseColorModel value to string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorModel | short | NoiseColorModel value. |

**Returns:**
java.lang.String - String value of color model.
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


Convert string value to GradientKind.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | string value. |

**Returns:**
int - GradientKind value.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Convert string value to NoiseColorModel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorModel | java.lang.String | string value. |

**Returns:**
short - NoiseColorModel value.
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

