---
title: "GradientHelper"
second_title: "Aspose.PSD för Java API-referens"
description: "Hjälparklass som implementerar konvertering av data för gradientegenskaper."
type: docs
weight: 34
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Hjälparklass som implementerar konvertering av data för gradientegenskaper.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL färgmodellens heltalskonstant för brusgradient. |
| [IntModelLAB](#IntModelLAB) | LBCL färgmodellens heltalskonstant för brusgradient. |
| [IntModelRGB](#IntModelRGB) | RGBC färgmodellens heltalskonstant för brusgradient. |
| [StrGradientNoise](#StrGradientNoise) | Strängkonstant för brusgradient. |
| [StrGradientSolid](#StrGradientSolid) | Strängkonstant för solid gradient. |
| [StrModelHSB](#StrModelHSB) | Strängkonstant för färgmodellen HSBL för brusgradient. |
| [StrModelLAB](#StrModelLAB) | Strängkonstant för färgmodellen LBCL för brusgradient. |
| [StrModelRGB](#StrModelRGB) | Strängkonstant för färgmodellen RGBC för brusgradient. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Konvertera GradientKind‑värdet till sträng. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Konverterar heltalsvärdet för brusfärgmodell till NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Konverterar NoiseColorModel-instans till heltalsvärdet för brusfärgmodell. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Konvertera NoiseColorModel‑värdet till sträng. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Konvertera strängvärde till GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Konvertera strängvärde till NoiseColorModel. |
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


HSBL färgmodellens heltalskonstant för brusgradient.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL färgmodellens heltalskonstant för brusgradient.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC färgmodellens heltalskonstant för brusgradient.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Strängkonstant för brusgradient.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Strängkonstant för solid gradient.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Strängkonstant för färgmodellen HSBL för brusgradient.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Strängkonstant för färgmodellen LBCL för brusgradient.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Strängkonstant för färgmodellen RGBC för brusgradient.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Konvertera GradientKind‑värdet till sträng.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gradientKind | int | GradientKind‑värde. |

**Returns:**
java.lang.String - strängvärde.
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


Konverterar heltalsvärdet för brusfärgmodell till NoiseColorModel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorModel | short | Heltalsvärde för brusfärgmodell. |

**Returns:**
short - NoiseColorModel-instans.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Konverterar NoiseColorModel-instans till heltalsvärdet för brusfärgmodell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorModel | short | NoiseColorModel-instans. |

**Returns:**
short - Heltalsvärde för brusgradientens färgmodell.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Konvertera NoiseColorModel‑värdet till sträng.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorModel | short | NoiseColorModel‑värde. |

**Returns:**
java.lang.String - Strängvärde för färgmodell.
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


Konvertera strängvärde till GradientKind.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String | strängvärde. |

**Returns:**
int - GradientKind‑värde.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Konvertera strängvärde till NoiseColorModel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorModel | java.lang.String | strängvärde. |

**Returns:**
short - NoiseColorModel‑värde.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

