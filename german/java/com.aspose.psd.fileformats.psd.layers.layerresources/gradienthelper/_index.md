---
title: "GradientHelper"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Hilfsklasse, die die Konvertierung von Daten für Gradient‑Eigenschaften implementiert."
type: docs
weight: 34
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Hilfsklasse, die die Konvertierung von Daten für Gradient‑Eigenschaften implementiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL-Farbmodell-Ganzzahlkonstante für Rauschgradient. |
| [IntModelLAB](#IntModelLAB) | LBCL-Farbmodell-Ganzzahlkonstante für Rauschgradient. |
| [IntModelRGB](#IntModelRGB) | RGBC-Farbmodell-Ganzzahlkonstante für Rauschgradient. |
| [StrGradientNoise](#StrGradientNoise) | Konstante für Rauschgradient-String. |
| [StrGradientSolid](#StrGradientSolid) | Konstante für Festgradient-String. |
| [StrModelHSB](#StrModelHSB) | HSBL-Farbmodell-String-Konstante für Rauschgradient. |
| [StrModelLAB](#StrModelLAB) | LBCL-Farbmodell-String-Konstante für Rauschgradient. |
| [StrModelRGB](#StrModelRGB) | RGBC-Farbmodell Zeichenkettenkonstante für Noise-Gradient. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Konvertiere GradientKind-Wert in eine Zeichenkette. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Konvertiert den Ganzzahlwert des Rauschfarbmodells in NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Konvertiert die NoiseColorModel-Instanz in den Ganzzahlwert des Rauschfarbmodells. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Konvertiere NoiseColorModel-Wert in eine Zeichenkette. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Konvertiere Zeichenkettenwert in GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Konvertiere Zeichenkettenwert in NoiseColorModel. |
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


HSBL-Farbmodell-Ganzzahlkonstante für Rauschgradient.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL-Farbmodell-Ganzzahlkonstante für Rauschgradient.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC-Farbmodell-Ganzzahlkonstante für Rauschgradient.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Konstante für Rauschgradient-String.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Konstante für Festgradient-String.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


HSBL-Farbmodell-String-Konstante für Rauschgradient.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


LBCL-Farbmodell-String-Konstante für Rauschgradient.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


RGBC-Farbmodell Zeichenkettenkonstante für Noise-Gradient.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Konvertiere GradientKind-Wert in eine Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gradientKind | int | GradientKind-Wert. |

**Returns:**
java.lang.String - Zeichenkettenwert.
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


Konvertiert den Ganzzahlwert des Rauschfarbmodells in NoiseColorModel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorModel | short | Ganzzahlwert des Rauschfarbmodells. |

**Returns:**
short - NoiseColorModel-Instanz.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Konvertiert die NoiseColorModel-Instanz in den Ganzzahlwert des Rauschfarbmodells.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorModel | short | NoiseColorModel-Instanz. |

**Returns:**
short - Ganzzahlwert des Noise-Gradienten-Farbmodells.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Konvertiere NoiseColorModel-Wert in eine Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorModel | short | NoiseColorModel-Wert. |

**Returns:**
java.lang.String - Zeichenkettenwert des Farbmodells.
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


Konvertiere Zeichenkettenwert in GradientKind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | java.lang.String | Zeichenkettenwert. |

**Returns:**
int - GradientKind-Wert.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Konvertiere Zeichenkettenwert in NoiseColorModel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorModel | java.lang.String | Zeichenkettenwert. |

**Returns:**
short - NoiseColorModel-Wert.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

