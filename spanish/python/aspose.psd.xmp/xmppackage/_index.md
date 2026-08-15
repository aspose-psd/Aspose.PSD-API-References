---
title: "Clase XmpPackage"
type: docs
weight: 430
url: /es/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Obtiene el URI del espacio de nombres. |
| prefijo | string | r | Obtiene el prefijo. |
| xml_namespace | string | r | Obtiene el espacio de nombres XML. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Agrega el valor. |
| clear() | Borra esta instancia. |
| [contains_key(key)](#contains_key_key_2) | Determina si la clave especificada contiene la clave. |
| [get_xml_value()](#get_xml_value__3) | Convierte el valor XMP a la representación XML. |
| [remove(key)](#remove_key_4) | Elimina el valor con la clave especificada. |
| [set_value(key, value)](#set_value_key_value_5) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Establece el valor del tipo XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Agrega el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | string | El valor al que agregar. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | El valor al que establecer. |

