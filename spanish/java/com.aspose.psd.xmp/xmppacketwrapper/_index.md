---
title: "XmpPacketWrapper"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Contiene el paquete xmp serializado, incluyendo encabezado y tráiler."
type: docs
weight: 20
url: /es/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Contiene el paquete xmp serializado, incluyendo encabezado y tráiler.

Un contenedor que consiste en un par de instrucciones de procesamiento XML (PIs) puede colocarse alrededor del elemento rdf:RDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Inicializa una nueva instancia de la clase XmpPacketWrapper. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Inicializa una nueva instancia de la clase XmpPacketWrapper. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Agrega el paquete. |
| [clearPackages()](#clearPackages--) | Elimina todos los XmpPackage dentro de XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determina si el paquete existe en el contenedor XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Obtiene la instrucción de procesamiento del encabezado. |
| [getMeta()](#getMeta--) | Obtiene los metadatos XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtiene el paquete por URI de espacio de nombres. |
| [getPackages()](#getPackages--) | Obtiene la matriz de XmpPackage dentro de XMP. |
| [getPackagesCount()](#getPackagesCount--) | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Obtiene el elemento RDF raíz. |
| [getTrailerPi()](#getTrailerPi--) | Obtiene la instrucción de procesamiento del tráiler. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Convierte el valor XMP a la representación XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Elimina el paquete XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Establece la instrucción de procesamiento del encabezado. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Establece los metadatos XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Establece el elemento RDF raíz. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Establece la instrucción de procesamiento del tráiler. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Inicializa una nueva instancia de la clase XmpPacketWrapper.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | El encabezado XMP de la instrucción de procesamiento. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | El tráiler XMP de la instrucción de procesamiento. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Los metadatos XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Inicializa una nueva instancia de la clase XmpPacketWrapper.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Agrega el paquete.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | El paquete. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Elimina todos los XmpPackage dentro de XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determina si el paquete existe en el contenedor XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI del esquema del paquete. |

**Returns:**
boolean - Devuelve true si el paquete con el URI de espacio de nombres especificado existe en el contenedor XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Obtiene la instrucción de procesamiento del encabezado.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Obtiene los metadatos XMP. Opcional.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtiene el paquete por URI de espacio de nombres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceUri | java.lang.String | El URI del esquema del paquete. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtiene la matriz de XmpPackage dentro de XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - La matriz de XmpPackage dentro de XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Obtiene la cantidad de paquetes dentro de la estructura XMP.

**Returns:**
int - La cantidad de paquetes dentro de la estructura XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Obtiene el elemento RDF raíz.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Obtiene la instrucción de procesamiento del tráiler.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Elimina el paquete XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | El paquete. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Establece la instrucción de procesamiento del encabezado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | La instrucción de procesamiento del encabezado. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Establece los metadatos XMP. Opcional.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Los metadatos XMP. Opcional. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Establece el elemento RDF raíz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | El elemento raíz RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Establece la instrucción de procesamiento del tráiler.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Instrucción de procesamiento del tráiler. |

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

