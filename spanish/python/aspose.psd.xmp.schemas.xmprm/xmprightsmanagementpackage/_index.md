---
title: "Clase XmpRightsManagementPackage"
type: docs
weight: 10
url: /es/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Inicializa una nueva instancia de la clase XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Establece el certificado. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Marca como contenido de gestión de derechos |
| [set_owners(owners)](#set_owners_owners_7) | Establece los propietarios. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Establece los términos de uso. |
| [set_value(key, value)](#set_value_key_value_9) | Establece el valor. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Establece la declaración web. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Establece el valor del tipo XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Inicializa una nueva instancia de la clase XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Establece el certificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificado | string | El certificado. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Marca como contenido de gestión de derechos

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | bool | si se establece a <c>true</c> que este es un recurso gestionado por derechos. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Establece los propietarios.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| propietarios | string | Los propietarios. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Establece los términos de uso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Los términos de uso. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | El valor al que agregar. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Establece la declaración web.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| web_statement_url | string | La URL de la declaración web. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | El valor al que establecer. |

