---
title: "GradientHelper"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe di supporto che implementa la conversione dei dati per le proprietà del gradiente."
type: docs
weight: 34
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Classe di supporto che implementa la conversione dei dati per le proprietà del gradiente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Costante intera del modello colore HSBL per il gradiente Noise. |
| [IntModelLAB](#IntModelLAB) | Costante intera del modello colore LBCL per il gradiente Noise. |
| [IntModelRGB](#IntModelRGB) | Costante intera del modello colore RGBC per il gradiente Noise. |
| [StrGradientNoise](#StrGradientNoise) | Costante stringa del gradiente di rumore. |
| [StrGradientSolid](#StrGradientSolid) | Costante stringa del gradiente solido. |
| [StrModelHSB](#StrModelHSB) | Costante stringa del modello colore HSBL per il gradiente di rumore. |
| [StrModelLAB](#StrModelLAB) | Costante stringa del modello colore LBCL per il gradiente di rumore. |
| [StrModelRGB](#StrModelRGB) | Costante stringa del modello colore RGBC per il gradiente di rumore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Converti il valore GradientKind in stringa. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Converte il valore intero del modello colore noise in NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Converte l'istanza di NoiseColorModel in valore intero del modello colore noise. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Converti il valore NoiseColorModel in stringa. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Converti il valore stringa in GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Converti il valore stringa in NoiseColorModel. |
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


Costante intera del modello colore HSBL per il gradiente Noise.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Costante intera del modello colore LBCL per il gradiente Noise.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Costante intera del modello colore RGBC per il gradiente Noise.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Costante stringa del gradiente di rumore.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Costante stringa del gradiente solido.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Costante stringa del modello colore HSBL per il gradiente di rumore.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Costante stringa del modello colore LBCL per il gradiente di rumore.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Costante stringa del modello colore RGBC per il gradiente di rumore.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Converti il valore GradientKind in stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gradientKind | int | Valore GradientKind. |

**Returns:**
java.lang.String - valore stringa.
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


Converte il valore intero del modello colore noise in NoiseColorModel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorModel | short | Valore intero del modello di colore del rumore. |

**Returns:**
short - istanza di NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Converte l'istanza di NoiseColorModel in valore intero del modello colore noise.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorModel | short | Istanza di NoiseColorModel. |

**Returns:**
short - Valore intero del modello di colore del gradiente di rumore.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Converti il valore NoiseColorModel in stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorModel | short | Valore di NoiseColorModel. |

**Returns:**
java.lang.String - Valore stringa del modello di colore.
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


Converti il valore stringa in GradientKind.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | java.lang.String | valore stringa. |

**Returns:**
int - valore di GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Converti il valore stringa in NoiseColorModel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorModel | java.lang.String | valore stringa. |

**Returns:**
short - valore di NoiseColorModel.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

