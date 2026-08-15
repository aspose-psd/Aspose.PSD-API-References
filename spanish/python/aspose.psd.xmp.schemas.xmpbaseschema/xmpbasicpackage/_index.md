---
title: "Clase XmpBasicPackage"
type: docs
weight: 10
url: /es/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Inicializa una nueva instancia de la clase [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Inicializa una nueva instancia de la clase [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Valor máximo de calificación. |
| RATING_MIN [static] | int | r | Valor mínimo de calificación. |
| RATING_REJECTED [static] | int | r | Valor de calificación rechazado. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Agrega la fecha de creación del recurso. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Agrega la fecha de creación del recurso. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Establece la herramienta creadora. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Establece el identificador. |
| [set_label(label)](#set_label_label_9) | Establece la etiqueta. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Agrega la fecha de última modificación de los metadatos. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Agrega la fecha de última modificación de los metadatos. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Agrega la fecha de última modificación del recurso. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Agrega la fecha de última modificación del recurso. |
| [set_rating(choise)](#set_rating_choise_14) | Establece la calificación. |
| [set_value(key, value)](#set_value_key_value_15) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Establece el valor del tipo XMP. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Inicializa una nueva instancia de la clase [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Inicializa una nueva instancia de la clase [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefijo | string | El prefijo. |
| namespace_uri | string | El URI del espacio de nombres. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Agrega la fecha de creación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| created_date | datetime | Fecha de creación. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Agrega la fecha de creación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| created_date | string | Fecha de creación. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Establece la herramienta creadora.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_tool | string | Nombre de la herramienta. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Establece el identificador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| idenfifier | string | El idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Establece la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| label | string | La etiqueta. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Agrega la fecha de última modificación de los metadatos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| metadata_date | datetime | Fecha de metadatos. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Agrega la fecha de última modificación de los metadatos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| metadata_date | string | Fecha de metadatos. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Agrega la fecha de última modificación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modified_date | datetime | Fecha de última modificación. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Agrega la fecha de última modificación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modified_date | string | Fecha de última modificación. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Establece la calificación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| choise | int | De -1 a 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | El valor al que establecer. |

