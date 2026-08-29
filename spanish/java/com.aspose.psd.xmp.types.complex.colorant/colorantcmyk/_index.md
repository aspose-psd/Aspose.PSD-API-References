---
title: "ColorantCmyk"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el colorante CMYK."
type: docs
weight: 13
url: /es/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Representa el colorante CMYK.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Inicializa una nueva instancia de la  ColorantCmyk  clase. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Inicializa una nueva instancia de la  ColorantCmyk  clase. |
## Campos

| Campo | Descripción |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Valor máximo de color en el colorante CMYK. |
| [ColorValueMin](#ColorValueMin) | Valor mínimo de color en el colorante CMYK. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Agrega la clave especificada. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Obtiene o establece el valor del componente negro. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Obtiene o establece el tipo del color. |
| [getCyan()](#getCyan--) | Obtiene o establece el valor del componente cian. |
| [getMagenta()](#getMagenta--) | Obtiene o establece el valor del componente magenta. |
| [getMode()](#getMode--) | Obtiene  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Obtiene el URI del espacio de nombres predeterminado. |
| [getPrefix()](#getPrefix--) | Obtiene el prefijo. |
| [getSwatchName()](#getSwatchName--) | Obtiene o establece el nombre de la muestra. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
| [getYellow()](#getYellow--) | Obtiene o establece el valor del componente amarillo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Obtiene o establece el valor del componente negro. |
| [setColorType(int value)](#setColorType-int-) | Obtiene o establece el tipo del color. |
| [setCyan(float value)](#setCyan-float-) | Obtiene o establece el valor del componente cian. |
| [setMagenta(float value)](#setMagenta-float-) | Obtiene o establece el valor del componente magenta. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Obtiene o establece el nombre de la muestra. |
| [setYellow(float value)](#setYellow-float-) | Obtiene o establece el valor del componente amarillo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Inicializa una nueva instancia de la  ColorantCmyk  clase.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Inicializa una nueva instancia de la  ColorantCmyk  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| negro | float | El valor del componente negro. |
| cian | float | El valor del componente de color cian. |
| magenta | float | El valor del componente magenta. |
| amarillo | float | El valor del componente amarillo. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Valor máximo de color en el colorante CMYK.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Valor mínimo de color en el colorante CMYK.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Agrega la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor agregado. |
| valor | java.lang.Object | El valor al que agregar. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Obtiene o establece el valor del componente negro.

Valor: El valor del componente negro.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtiene o establece el tipo del color.

Valor: El tipo del color.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Obtiene o establece el valor del componente cian.

Valor: El valor del componente cian.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Obtiene o establece el valor del componente magenta.

Valor: El valor del componente magenta.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Obtiene  ColorMode .

Valor: El modo de color.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtiene el URI del espacio de nombres predeterminado.

**Returns:**
java.lang.String - El URI del espacio de nombres predeterminado.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtiene el prefijo.

**Returns:**
java.lang.String - El prefijo.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Obtiene o establece el nombre de la muestra.

Valor: El nombre de la muestra.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtiene el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Obtiene o establece el valor del componente amarillo.

Valor: El valor del componente amarillo.

**Returns:**
float
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Obtiene o establece el valor del componente negro.

Valor: El valor del componente negro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtiene o establece el tipo del color.

Valor: El tipo del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Obtiene o establece el valor del componente cian.

Valor: El valor del componente cian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Obtiene o establece el valor del componente magenta.

Valor: El valor del componente magenta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Obtiene o establece el nombre de la muestra.

Valor: El nombre de la muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Obtiene o establece el valor del componente amarillo.

Valor: El valor del componente amarillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

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

