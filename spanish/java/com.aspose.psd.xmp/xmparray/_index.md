---
title: "XmpArray"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa Xmp Array en XmpPackage."
type: docs
weight: 12
url: /es/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Representa Xmp Array en XmpPackage. todo: Array puede contener datos complejos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Inicializa una nueva instancia de la clase XmpArray. |
| [XmpArray(int type)](#XmpArray-int-) | Inicializa una nueva instancia de la clase XmpArray. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Agrega un nuevo elemento. |
| [addItem(String item)](#addItem-java.lang.String-) | Agrega un nuevo elemento. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Obtiene la matriz de valores dentro de [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Obtiene la matriz de valores dentro de  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve un  System.String  que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Inicializa una nueva instancia de la clase XmpArray.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de matriz. |
| elementos | java.lang.String[] | La lista de elementos. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Inicializa una nueva instancia de la clase XmpArray.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de matriz. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Agrega un nuevo elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | El elemento que se añadirá a la lista de elementos. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Agrega un nuevo elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | java.lang.String | El elemento que se añadirá a la lista de elementos. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


Obtiene la matriz de valores dentro de [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Obtiene la matriz de valores dentro de  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
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

