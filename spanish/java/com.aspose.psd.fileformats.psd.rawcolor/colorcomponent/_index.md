---
title: "ColorComponent"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El componente de color es una abstracción sobre Valor de Canal y Valor de Canal."
type: docs
weight: 10
url: /es/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

El componente de color es una abstracción sobre Valor de Canal y Valor de Canal. Cualquier color se compone de una matriz de ColorComponent
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Inicializa una nueva instancia de la clase [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Obtiene la profundidad de bits del Componente/Canal de Color |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtiene la descripción del Componente de Color |
| [getFullName()](#getFullName--) | Obtiene el nombre completo del componente de color con el nombre y la descripción separada por espacios |
| [getName()](#getName--) | Obtiene el nombre del componente de color. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Obtiene los nombres completos permitidos. |
| [getValue()](#getValue--) | Obtiene o establece el valor. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Obtiene o establece el valor. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Inicializa una nueva instancia de la clase [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Por favor, verifica

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitDepth | byte | La profundidad de bits. |
| fullName | java.lang.String | El nombre completo. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Obtiene la profundidad de bits del Componente/Canal de Color

Valor: La profundidad de bits.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtiene la descripción del Componente de Color

Valor: La descripción.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Obtiene el nombre completo del componente de color con el nombre y la descripción separada por espacios

Valor: El nombre completo.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre del componente de color.

Valor: El nombre.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Obtiene los nombres completos permitidos.

Valor: Los nombres completos permitidos.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Obtiene o establece el valor. Tenga en cuenta que, si intenta establecer un valor que supera lo que puede almacenarse en la profundidad de bits actual, obtendrá una excepción.

Valor: El valor.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Obtiene o establece el valor. Tenga en cuenta que, si intenta establecer un valor que supera lo que puede almacenarse en la profundidad de bits actual, obtendrá una excepción.

Valor: El valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

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

