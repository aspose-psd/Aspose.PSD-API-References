---
title: "Clase XmpMediaManagementPackage"
type: docs
weight: 10
url: /es/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Inicializa una nueva instancia de la clase XmpMediaManagementPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Obtiene el URI del espacio de nombres. |
| prefijo | string | r | Obtiene el prefijo. |
| xml_namespace | string | r | Obtiene el espacio de nombres XML. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Agrega una propiedad de cadena. |
| clear() | Borra esta instancia. |
| [contains_key(key)](#contains_key_key_2) | Determina si la clave especificada contiene la clave. |
| [get_xml_value()](#get_xml_value__3) | Convierte el valor XMP a la representación XML. |
| [remove(key)](#remove_key_4) | Elimina el valor con la clave especificada. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Establece el derivado de. |
| [set_document_id(guid)](#set_document_id_guid_6) | Establece el identificador del documento. |
| [set_document_id(guid)](#set_document_id_guid_7) | Establece el identificador del documento. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Establece el id de instancia. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Establece el id de instancia. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Establece el id del documento original. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Establece el id del documento original. |
| [set_value(key, value)](#set_value_key_value_12) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Establece el valor del tipo XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Inicializa una nueva instancia de la clase XmpMediaManagementPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Agrega una propiedad de cadena.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | string | El valor de cadena. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Determina si la clave especificada contiene la clave.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave a comprobar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve true si la clave especificada contiene la clave. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a la representación XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Elimina el valor con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor eliminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve true si el valor con la clave especificada fue eliminado. |


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Establece el derivado de.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | La referencia del recurso. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Establece el identificador del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | Guid | El identificador único. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Establece el identificador del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Establece el id de instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | Guid | El identificador único. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Establece el id de instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Establece el id del documento original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | Guid | El identificador único. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Establece el id del documento original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | El valor al que establecer. |

