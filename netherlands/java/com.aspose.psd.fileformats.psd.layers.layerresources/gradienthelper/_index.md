---
title: "GradientHelper"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Helperklasse die conversie van gegevens voor gradienteigenschappen implementeert."
type: docs
weight: 34
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Helperklasse die conversie van gegevens voor gradienteigenschappen implementeert.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL kleurmodel gehele‑getal constante voor ruisverloop. |
| [IntModelLAB](#IntModelLAB) | LBCL kleurmodel gehele‑getal constante voor ruisverloop. |
| [IntModelRGB](#IntModelRGB) | RGBC kleurmodel gehele‑getal constante voor ruisverloop. |
| [StrGradientNoise](#StrGradientNoise) | Noise gradient tekenreeks constante. |
| [StrGradientSolid](#StrGradientSolid) | Solid gradient tekenreeks constante. |
| [StrModelHSB](#StrModelHSB) | HSBL kleurmodel tekenreeks constante voor Noise gradient. |
| [StrModelLAB](#StrModelLAB) | LBCL kleurmodel tekenreeks constante voor Noise gradient. |
| [StrModelRGB](#StrModelRGB) | RGBC kleurmodel tekenreeks constante voor Noise gradient. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Converteer GradientKind-waarde naar tekenreeks. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Converteert gehele‑getalwaarde van ruiskleurmodel naar NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Converteert NoiseColorModel‑instantie naar gehele‑getalwaarde van ruiskleurmodel. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Converteer NoiseColorModel-waarde naar tekenreeks. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Converteer tekenreekswaarde naar GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Converteer tekenreekswaarde naar NoiseColorModel. |
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


HSBL kleurmodel gehele‑getal constante voor ruisverloop.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL kleurmodel gehele‑getal constante voor ruisverloop.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC kleurmodel gehele‑getal constante voor ruisverloop.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Noise gradient tekenreeks constante.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Solid gradient tekenreeks constante.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


HSBL kleurmodel tekenreeks constante voor Noise gradient.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


LBCL kleurmodel tekenreeks constante voor Noise gradient.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


RGBC kleurmodel tekenreeks constante voor Noise gradient.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Converteer GradientKind-waarde naar tekenreeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gradientKind | int | GradientKind‑waarde. |

**Returns:**
java.lang.String - tekenreekswaarde.
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


Converteert gehele‑getalwaarde van ruiskleurmodel naar NoiseColorModel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorModel | short | Integer‑waarde van het ruiskleurmodel. |

**Returns:**
short - NoiseColorModel‑instantie.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Converteert NoiseColorModel‑instantie naar gehele‑getalwaarde van ruiskleurmodel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorModel | short | NoiseColorModel‑instantie. |

**Returns:**
short - Integer‑waarde van het Noise gradient‑kleurmodel.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Converteer NoiseColorModel-waarde naar tekenreeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorModel | short | NoiseColorModel‑waarde. |

**Returns:**
java.lang.String - tekenreekswaarde van het kleurmodel.
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


Converteer tekenreekswaarde naar GradientKind.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String | tekenreekswaarde. |

**Returns:**
int - GradientKind‑waarde.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Converteer tekenreekswaarde naar NoiseColorModel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorModel | java.lang.String | tekenreekswaarde. |

**Returns:**
short - NoiseColorModel‑waarde.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

