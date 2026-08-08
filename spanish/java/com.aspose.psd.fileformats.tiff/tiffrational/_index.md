---
title: "TiffRational"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El tipo racional TIFF."
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

El tipo racional TIFF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffRational()](#TiffRational--) | Inicializa una nueva instancia de la clase TiffRational. |
| [TiffRational(long value)](#TiffRational-long-) | Inicializa una nueva instancia de la clase TiffRational. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Inicializa una nueva instancia de la clase TiffRational. |
## Campos

| Campo | Descripción |
| --- | --- |
| [Epsilon](#Epsilon) | El epsilon para el cálculo de fracciones |
## Métodos

| Método | Descripción |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(float value)](#approximateFraction-float-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Aproxima el valor proporcionado a una fracción. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Obtiene el denominador. |
| [getNominator()](#getNominator--) | Obtiene el nominador. |
| [getValue()](#getValue--) | Obtiene el valor flotante. |
| [getValueD()](#getValueD--) | Obtiene el valor doble. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve un  System.String  que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Inicializa una nueva instancia de la clase TiffRational.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Inicializa una nueva instancia de la clase TiffRational.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | long | El valor del nominador. |

El nominador se usará como el valor especificado y el denominador será igual a 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Inicializa una nueva instancia de la clase TiffRational.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nominador | long | El nominador. |
| denominador | long | El denominador. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


El epsilon para el cálculo de fracciones

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Object para comparar con esta instancia. |

**Returns:**
boolean -  true  si el Object especificado es igual a esta instancia; de lo contrario,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Obtiene el denominador.

Valor: El denominador.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Obtiene el nominador.

Valor: El nominador.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Obtiene el valor flotante.

Valor: El valor flotante.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Obtiene el valor doble.

Valor: El valor doble.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Devuelve un  System.String  que representa esta instancia.

**Returns:**
java.lang.String - Un  System.String  que representa esta instancia.
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

