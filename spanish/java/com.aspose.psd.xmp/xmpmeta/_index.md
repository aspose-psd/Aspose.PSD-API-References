---
title: "XmpMeta"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa xmpmeta."
type: docs
weight: 17
url: /es/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Representa xmpmeta. Opcional. El propósito de este elemento es identificar los metadatos XMP dentro de texto XML general que podría contener otros usos no XMP de RDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Inicializa una nueva instancia de la  XmpMeta  clase. |
| [XmpMeta()](#XmpMeta--) | Inicializa una nueva instancia de la  XmpMeta  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Agrega el atributo. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Asigna el elemento XMP especificado al actual. |
| [clearAttributes()](#clearAttributes--) | Elimina todos los atributos. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [equals(Object other)](#equals-java.lang.Object-) | Determina si el  System.Object  especificado , es igual a esta instancia. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Obtiene o establece la versión del toolkit Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtiene el atributo. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Obtiene o establece la versión del toolkit Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Inicializa una nueva instancia de la  XmpMeta  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Versión del toolkit Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Inicializa una nueva instancia de la  XmpMeta  clase.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Agrega el atributo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attribute | java.lang.String | El attribute. |
| valor | java.lang.String | El valor. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Asigna el elemento XMP especificado al actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | El elemento XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Elimina todos los atributos.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina si el  System.Object  especificado , es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | java.lang.Object | El  System.Object  para comparar con esta instancia. |

**Returns:**
boolean - true si el System.Object especificado es igual a esta instancia; de lo contrario, false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Obtiene o establece la versión del toolkit Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Obtiene el atributo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attribute | java.lang.String | El attribute. |

**Returns:**
java.lang.String - Devuelve el atributo para el nombre de atributo especificado.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - true si el objeto actual es igual al parámetro other; de lo contrario, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - true si el objeto actual es igual al parámetro other; de lo contrario, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Obtiene o establece la versión del toolkit Adobe Xmp.

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

