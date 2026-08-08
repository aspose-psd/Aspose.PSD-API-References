---
title: "ResourceEvent"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Contiene dimensiones para un objeto dibujado."
type: docs
weight: 10
url: /es/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contiene dimensiones para un objeto dibujado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Inicializa una nueva instancia de la clase ResourceEvent. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Agrega la clave especificada. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Obtiene la acción. |
| [getActionDate()](#getActionDate--) | Obtiene o establece la fecha de la acción. |
| [getChanged()](#getChanged--) | Obtiene la lista delimitada por punto y coma de las partes del recurso que fueron modificadas desde el historial de eventos anterior. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Obtiene el valor de xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtiene el URI del espacio de nombres predeterminado. |
| [getParameters()](#getParameters--) | Obtiene o establece la descripción adicional de la acción. |
| [getPrefix()](#getPrefix--) | Obtiene el prefijo. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Obtiene o establece el nombre del agente de software. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Establece la acción. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Obtiene o establece la fecha de la acción. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Establece la lista delimitada por punto y coma de las partes del recurso que fueron modificadas desde el historial de eventos anterior. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Obtiene o establece el valor de xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Obtiene o establece la descripción adicional de la acción. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Obtiene o establece el nombre del agente de software. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Inicializa una nueva instancia de la clase ResourceEvent.

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
### getAction() {#getAction--}
```
public String getAction()
```


Obtiene la acción.

Los valores definidos son: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Los nuevos valores deben ser verbos en pasado.

**Returns:**
java.lang.String - La acción.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Obtiene o establece la fecha de la acción.

**Returns:**
java.util.Date - La fecha de la acción.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Obtiene la lista delimitada por punto y coma de las partes del recurso que fueron modificadas desde el historial de eventos anterior.

**Returns:**
java.lang.String - La lista delimitada por punto y coma de las partes del recurso que fueron modificadas desde el historial de eventos anterior.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Obtiene el valor de xmpMM:InstanceId.

**Returns:**
java.util.UUID - El valor de xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtiene el URI del espacio de nombres predeterminado.

**Returns:**
java.lang.String - El URI del espacio de nombres predeterminado.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Obtiene o establece la descripción adicional de la acción.

Valor: La descripción adicional de la acción.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtiene el prefijo.

**Returns:**
java.lang.String - El prefijo.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Obtiene o establece el nombre del agente de software.

**Returns:**
java.lang.String - El nombre del agente de software.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Establece la acción.

Los valores definidos son: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Los nuevos valores deben ser verbos en pasado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La acción. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Obtiene o establece la fecha de la acción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date | La fecha de la acción. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Establece la lista delimitada por punto y coma de las partes del recurso que fueron modificadas desde el historial de eventos anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Obtiene o establece el valor de xmpMM:InstanceId.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID | El valor de xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Obtiene o establece la descripción adicional de la acción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La descripción adicional de la acción. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Obtiene o establece el nombre del agente de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre del agente de software. |

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

