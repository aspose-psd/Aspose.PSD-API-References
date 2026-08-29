---
title: "XmpBasicPackage"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el espacio de nombres básico de XMP"
type: docs
weight: 10
url: /es/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Representa el espacio de nombres básico de XMP
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Inicializa una nueva instancia de la clase XmpBasicPackage. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase XmpBasicPackage. |
## Campos

| Campo | Descripción |
| --- | --- |
| [RatingMax](#RatingMax) | Valor máximo de la calificación. |
| [RatingMin](#RatingMin) | Valor mínimo de la calificación. |
| [RatingRejected](#RatingRejected) | Valor rechazado de la calificación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Agrega el espacio de nombres de tipo complejo. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Agrega la propiedad de cadena. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Asigna el paquete XMP especificado al actual. |
| [clear()](#clear--) | Limpia esta instancia. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Combina el paquete. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina si la clave especificada contiene la clave. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Obtiene las claves en el paquete XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtiene el URI del espacio de nombres. |
| [getPrefix()](#getPrefix--) | Obtiene el prefijo. |
| [getXmlNamespace()](#getXmlNamespace--) | Obtiene el espacio de nombres XML. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtiene o establece el Object con la clave especificada. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Elimina el valor con la clave especificada. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Agrega la fecha de creación del recurso. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Agrega la fecha de creación del recurso. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Establece la herramienta creadora. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Establece el identificador. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Establece la etiqueta. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Agrega la fecha de última modificación de los metadatos. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Agrega la fecha de última modificación de los metadatos. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Agrega la fecha de última modificación del recurso. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Agrega la fecha de última modificación del recurso. |
| [setRating(int choise)](#setRating-int-) | Establece la calificación. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Establece el valor. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Establece el valor booleano de XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Establece el identificador único de XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Establece el valor de tipo de XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Obtiene o establece el Object con la clave especificada. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Inicializa una nueva instancia de la clase XmpBasicPackage.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Inicializa una nueva instancia de la clase XmpBasicPackage.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | java.lang.String | El prefijo. |
| namespaceUri | java.lang.String | El URI del espacio de nombres. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Valor máximo de la calificación.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Valor mínimo de la calificación.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Valor rechazado de la calificación.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Agrega el espacio de nombres de tipo complejo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typePrefix | java.lang.String | El prefijo de tipo. |
| typeNamespaceUri | java.lang.String | El URI del espacio de nombres de tipo. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Agrega la propiedad de cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor agregado. |
| valor | java.lang.String | El valor de cadena. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Asigna el paquete XMP especificado al actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | El paquete XMP. |

### clear() {#clear--}
```
public void clear()
```


Limpia esta instancia.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Combina el paquete.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | El otro paquete a combinar. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determina si la clave especificada contiene la clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave a comprobar. |

**Returns:**
boolean - Devuelve true si la clave especificada contiene la clave.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Obtiene las claves en el paquete XMP.

Valor: Las claves en el paquete XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtiene el URI del espacio de nombres.

Valor: El URI del espacio de nombres.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtiene el prefijo.

Valor: El prefijo.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Obtiene el espacio de nombres XML.

Valor: El espacio de nombres XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Obtiene o establece el Object con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave que identifica el valor. Valor: El Object. |

**Returns:**
java.lang.Object - Devuelve el Object con la clave especificada.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Devuelve un enumerador que recorre la colección.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un  T:System.Collections.Generic.IEnumerator1  que puede usarse para iterar a través de la colección.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Elimina el valor con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación de cadena de la clave que se identifica con el valor eliminado. |

**Returns:**
boolean - Devuelve true si el valor con la clave especificada fue eliminado.
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Agrega la fecha de creación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | java.lang.String | Fecha de creación. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Agrega la fecha de creación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Fecha de creación. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Establece la herramienta creadora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorTool | java.lang.String | Nombre de la herramienta. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Establece el identificador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idenfifier | java.lang.String[] | El idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Establece la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | java.lang.String | La etiqueta. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Agrega la fecha de última modificación de los metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadataDate | java.lang.String | Fecha de metadatos. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Agrega la fecha de última modificación de los metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Fecha de metadatos. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Agrega la fecha de última modificación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modifiedDate | java.lang.String | Última fecha de modificación. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Agrega la fecha de última modificación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Última fecha de modificación. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Establece la calificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elección | int | De -1 a 5 |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Establece el valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor agregado. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | El valor al que agregar. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Establece el valor booleano de XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor establecido. |
| boolValue | java.lang.String | El valor booleano. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Establece el identificador único de XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor GUID establecido. |
| guid | java.lang.String | El identificador único. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Establece el valor de tipo de XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | El valor a establecer. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Obtiene o establece el Object con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave que identifica el valor. Valor: El Object. |
| valor | java.lang.Object |  |

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

