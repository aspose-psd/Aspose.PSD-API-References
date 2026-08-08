---
title: "XmpRdfRoot"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el elemento rdfRDF."
type: docs
weight: 21
url: /es/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Representa el elemento rdf:RDF. Un solo paquete XMP debe serializarse usando un único elemento XML rdf:RDF. El contenido del elemento rdf:RDF debe consistir en cero o más elementos rdf:Description.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Inicializa una nueva instancia de la clase  XmpRdfRoot  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Agrega el atributo. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Asigna el elemento XMP especificado al actual. |
| [clearAttributes()](#clearAttributes--) | Elimina todos los atributos. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtiene el atributo. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Obtiene el URI del espacio de nombres por prefijo específico. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor xmp a la representación xml. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Agrega el URI del espacio de nombres mediante prefijo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Inicializa una nueva instancia de la clase  XmpRdfRoot  .

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  Object  para comparar con esta instancia. |

**Returns:**
boolean -  true  si el  Object  especificado es igual a esta instancia; de lo contrario,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Obtiene el URI del espacio de nombres por prefijo específico. El prefijo puede comenzar sin xmlns.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | java.lang.String | El prefijo. |

**Returns:**
java.lang.String - Devuelve un URI de esquema de paquete.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor xmp a la representación xml.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a cadena XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Agrega el URI del espacio de nombres mediante prefijo. El prefijo puede comenzar sin xmlns.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | java.lang.String | El prefijo. |
| namespaceUri | java.lang.String | URI del esquema del paquete. |

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

