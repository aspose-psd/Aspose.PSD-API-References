---
title: "XmpHeaderPi"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa la instrucción de procesamiento del encabezado XMP."
type: docs
weight: 16
url: /es/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Representa la instrucción de procesamiento del encabezado XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Inicializa una nueva instancia de la clase XmpHeaderPi. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Inicializa una nueva instancia de la clase XmpHeaderPi. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el  System.Object  especificado , es igual a esta instancia. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Representa el GUID del encabezado. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Representa el GUID del encabezado. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Inicializa una nueva instancia de la clase XmpHeaderPi.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Inicializa una nueva instancia de la clase XmpHeaderPi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| guid | java.lang.String | El identificador único. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el  System.Object  especificado , es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  para comparar con esta instancia. |

**Returns:**
boolean - true si el System.Object especificado es igual a esta instancia; de lo contrario, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


Representa el GUID del encabezado.

El texto del PI del encabezado contiene un GUID, lo que hace que sea improbable que aparezca por accidente en el flujo de datos.

**Returns:**
java.lang.String
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
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Un objeto para comparar con este objeto. |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Representa el GUID del encabezado.

El texto del PI del encabezado contiene un GUID, lo que hace que sea improbable que aparezca por accidente en el flujo de datos.

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

