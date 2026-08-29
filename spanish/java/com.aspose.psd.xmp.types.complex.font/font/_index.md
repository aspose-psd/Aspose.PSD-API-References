---
title: "Fuente"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa la fuente XMP."
type: docs
weight: 10
url: /es/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Representa la fuente XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Font()](#Font--) | Inicializa una nueva instancia de la  Font  clase. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Inicializa una nueva instancia de la  Font  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Agrega la clave especificada. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Obtiene o establece la matriz de nombres de archivo para las fuentes que componen una fuente compuesta. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Obtiene o establece el estilo de fuente. |
| [getFontFamily()](#getFontFamily--) | Obtiene o establece la familia de fuentes. |
| [getFontFileName()](#getFontFileName--) | Obtiene o establece el nombre de archivo de la fuente sin ruta completa. |
| [getFontName()](#getFontName--) | Obtiene o establece el nombre de fuente PostScript. |
| [getFontType()](#getFontType--) | Obtiene o establece el tipo de fuente. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtiene el URI del espacio de nombres predeterminado. |
| [getPrefix()](#getPrefix--) | Obtiene el prefijo. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión de la fuente. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Obtiene o establece un valor que indica si esta fuente es compuesta. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Obtiene o establece la matriz de nombres de archivo para las fuentes que componen una fuente compuesta. |
| [setComposite(boolean value)](#setComposite-boolean-) | Obtiene o establece un valor que indica si esta fuente es compuesta. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Obtiene o establece el estilo de fuente. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Obtiene o establece la familia de fuentes. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Obtiene o establece el nombre de archivo de la fuente sin ruta completa. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Obtiene o establece el nombre de fuente PostScript. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Obtiene o establece el tipo de fuente. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Obtiene o establece la versión de la fuente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Inicializa una nueva instancia de la  Font  clase.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Inicializa una nueva instancia de la  Font  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamily | java.lang.String | Familia de fuentes. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Obtiene o establece la matriz de nombres de archivo para las fuentes que componen una fuente compuesta.

Valor: La matriz de nombres de archivo para las fuentes que componen una fuente compuesta.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Obtiene o establece el estilo de fuente.

Valor: El estilo de fuente.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Obtiene o establece la familia de fuentes.

Valor: La familia de fuentes.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Obtiene o establece el nombre de archivo de la fuente sin ruta completa.

Valor: El nombre de archivo de la fuente sin ruta completa.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Obtiene o establece el nombre de fuente PostScript.

Valor: El nombre de la fuente PostScript.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Obtiene o establece el tipo de fuente.

TrueType, Type 1, Open Type, y así sucesivamente. Valor: El tipo de fuente.

**Returns:**
java.lang.String
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
### getVersion() {#getVersion--}
```
public String getVersion()
```


Obtiene o establece la versión de la fuente.

/versión para fuentes Type1 nameId 5 para Apple True Type y OpenType /CIDFontVersion para fuentes CID La cadena vacía para fuentes bitmap Valor: La versión de la fuente.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtiene el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Obtiene o establece un valor que indica si esta fuente es compuesta.

Valor:  true  si esta fuente es compuesta; de lo contrario,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Obtiene o establece la matriz de nombres de archivo para las fuentes que componen una fuente compuesta.

Valor: La matriz de nombres de archivo para las fuentes que componen una fuente compuesta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Obtiene o establece un valor que indica si esta fuente es compuesta.

Valor:  true  si esta fuente es compuesta; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Obtiene o establece el estilo de fuente.

Valor: El estilo de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Obtiene o establece la familia de fuentes.

Valor: La familia de fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Obtiene o establece el nombre de archivo de la fuente sin ruta completa.

Valor: El nombre de archivo de la fuente sin ruta completa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Obtiene o establece el nombre de fuente PostScript.

Valor: El nombre de la fuente PostScript.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Obtiene o establece el tipo de fuente.

TrueType, Type 1, Open Type, y así sucesivamente. Valor: El tipo de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Obtiene o establece la versión de la fuente.

/versión para fuentes Type1 nameId 5 para Apple True Type y OpenType /CIDFontVersion para fuentes CID La cadena vacía para fuentes bitmap Valor: La versión de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

