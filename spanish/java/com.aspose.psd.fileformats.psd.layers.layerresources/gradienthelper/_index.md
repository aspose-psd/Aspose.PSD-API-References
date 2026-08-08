---
title: "GradientHelper"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase auxiliar que implementa la conversión de datos para propiedades de degradado."
type: docs
weight: 34
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Clase auxiliar que implementa la conversión de datos para propiedades de degradado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Constante entera del modelo de color HSBL para el gradiente de ruido. |
| [IntModelLAB](#IntModelLAB) | Constante entera del modelo de color LBCL para el gradiente de ruido. |
| [IntModelRGB](#IntModelRGB) | Constante entera del modelo de color RGBC para el gradiente de ruido. |
| [StrGradientNoise](#StrGradientNoise) | Constante de cadena de degradado de ruido. |
| [StrGradientSolid](#StrGradientSolid) | Constante de cadena de degradado sólido. |
| [StrModelHSB](#StrModelHSB) | Constante de cadena del modelo de color HSBL para el degradado de ruido. |
| [StrModelLAB](#StrModelLAB) | Constante de cadena del modelo de color LBCL para el degradado de ruido. |
| [StrModelRGB](#StrModelRGB) | Constante de cadena del modelo de color RGBC para el degradado de ruido. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Convertir el valor de GradientKind a cadena. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Convierte el valor entero del modelo de color de ruido a NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Convierte la instancia de NoiseColorModel a valor entero del modelo de color de ruido. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Convertir el valor de NoiseColorModel a cadena. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Convertir el valor de cadena a GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Convertir el valor de cadena a NoiseColorModel. |
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


Constante entera del modelo de color HSBL para el gradiente de ruido.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Constante entera del modelo de color LBCL para el gradiente de ruido.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Constante entera del modelo de color RGBC para el gradiente de ruido.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Constante de cadena de degradado de ruido.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Constante de cadena de degradado sólido.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Constante de cadena del modelo de color HSBL para el degradado de ruido.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Constante de cadena del modelo de color LBCL para el degradado de ruido.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Constante de cadena del modelo de color RGBC para el degradado de ruido.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Convertir el valor de GradientKind a cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gradientKind | int | Valor de GradientKind. |

**Returns:**
java.lang.String - valor de cadena.
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


Convierte el valor entero del modelo de color de ruido a NoiseColorModel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorModel | short | Valor entero del modelo de color de ruido. |

**Returns:**
short - instancia de NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Convierte la instancia de NoiseColorModel a valor entero del modelo de color de ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorModel | short | Instancia de NoiseColorModel. |

**Returns:**
short - Valor entero del modelo de color de gradiente de ruido.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Convertir el valor de NoiseColorModel a cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorModel | short | Valor de NoiseColorModel. |

**Returns:**
java.lang.String - Valor de cadena del modelo de color.
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


Convertir el valor de cadena a GradientKind.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String | valor de cadena. |

**Returns:**
int - valor de GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Convertir el valor de cadena a NoiseColorModel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorModel | java.lang.String | valor de cadena. |

**Returns:**
short - valor de NoiseColorModel.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

