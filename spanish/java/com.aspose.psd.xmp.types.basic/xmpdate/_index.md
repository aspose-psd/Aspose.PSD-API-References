---
title: "XmpDate"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa la fecha en el paquete XMP."
type: docs
weight: 11
url: /es/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Representa la fecha en el paquete XMP.

Un valor de fecha y hora se representa usando un subconjunto de los formatos definidos en Formatos de Fecha y Hora: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Inicializa una nueva instancia de la clase XmpDate. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Inicializa una nueva instancia de la clase XmpDate. |
## Campos

| Campo | Descripción |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | La cadena de formato ISO 8601 (ida y vuelta). |
## Métodos

| Método | Descripción |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Obtiene la cadena de formato para el valor actual. |
| [getValue()](#getValue--) | Obtiene o establece el valor de fecha. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Devuelve el valor de cadena contenido en formato XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Obtiene o establece el valor de fecha. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Inicializa una nueva instancia de la clase XmpDate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dateTime | java.util.Date | Un valor de fecha y hora que se representa usando un subconjunto del formato ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Inicializa una nueva instancia de la clase XmpDate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dateString | java.lang.String | La representación en cadena de la fecha. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


La cadena de formato ISO 8601 (ida y vuelta).

Ver más: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Obtiene la cadena de formato para el valor actual.

Valor: La cadena de formato para el valor actual.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Obtiene o establece el valor de fecha.

Valor: El valor de fecha.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Devuelve el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Obtiene o establece el valor de fecha.

Valor: El valor de fecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

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

