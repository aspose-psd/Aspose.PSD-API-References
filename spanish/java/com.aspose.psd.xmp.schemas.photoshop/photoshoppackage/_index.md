---
title: "PhotoshopPackage"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el espacio de nombres de Adobe Photoshop."
type: docs
weight: 12
url: /es/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Representa el espacio de nombres de Adobe Photoshop.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Inicializa una nueva instancia de la clase PhotoshopPackage. |
## Campos

| Campo | Descripción |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Valor máximo de urgencia. |
| [UrgencyMin](#UrgencyMin) | Valor mínimo de urgencia. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtiene o establece el  Object  con la clave especificada. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Elimina el valor con la clave especificada. |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Establece la posición del autor. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Establece el escritor del subtítulo. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Establece la categoría. |
| [setCity(String city)](#setCity-java.lang.String-) | Establece la ciudad. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Establece el modo de color. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Establece el país. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Establece la fecha de creación. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Establece el crédito. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Establece los ancestros del documento. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Establece el titular. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Establece el historial. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Establece el perfil icc. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Establece las instrucciones. |
| [setSource(String source)](#setSource-java.lang.String-) | Establece la fuente. |
| [setState(String state)](#setState-java.lang.String-) | Establece el estado. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Establece categorías suplementarias. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Establece la referencia de transmisión. |
| [setUrgency(int urgency)](#setUrgency-int-) | Establece la urgencia. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Establece el valor. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Establece el valor booleano de XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Establece el identificador único de XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Establece el valor de tipo de XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Establece el  Object  con la clave especificada. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Inicializa una nueva instancia de la clase PhotoshopPackage.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Valor máximo de urgencia.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Valor mínimo de urgencia.

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


Obtiene o establece el  Object  con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave que identifica el valor. |

**Returns:**
java.lang.Object - Devuelve el  Object  con la clave especificada.
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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Establece la posición del autor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| authorsPosition | java.lang.String | La posición de los autores. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Establece el escritor del subtítulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| captionWriter | java.lang.String | El escritor de subtítulos. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Establece la categoría.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| category | java.lang.String | La categoría. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Establece la ciudad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| city | java.lang.String | El nombre de la ciudad. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Establece el modo de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorMode | byte | El modo de color. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Establece el país.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| country | java.lang.String | El país. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Establece la fecha de creación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | java.util.Date | La fecha de creación. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Establece el crédito.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| credit | java.lang.String | El crédito. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Establece los ancestros del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancestors | java.lang.String[] | Los ancestros. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Establece el titular.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headline | java.lang.String | El titular. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Establece el historial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| history | java.lang.String | La historia. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Establece el perfil icc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iccProfile | java.lang.String | El perfil icc. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Establece las instrucciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instrucciones | java.lang.String | Las instrucciones. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Establece la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fuente | java.lang.String | La fuente. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Establece el estado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| estado | java.lang.String | El estado. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Establece categorías suplementarias.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | Las categorías suplementarias. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Establece la referencia de transmisión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transmissionReference | java.lang.String | La referencia de transmisión. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Establece la urgencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | urgency | int | La urgencia. |

La urgencia debe estar en el rango de 1 a 8. |

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


Establece el  Object  con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave que identifica el valor. |
| valor | java.lang.Object | El  Object  valor. |

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

