---
title: "Clase PdfPackage"
type: docs
weight: 10
url: /es/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Inicializa una nueva instancia de la clase PdfPackage |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | Establece las palabras clave. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Establece la versión del PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Establece el nombre de la herramienta que creó el PDF. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Establece el trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Establece el valor del tipo XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Inicializa una nueva instancia de la clase PdfPackage

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Establece las palabras clave.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| keywords | string | Las palabras clave. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Establece la versión del PDF.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| version | string | Versión PDF, por ejemplo: 1.0, 1.3 etc. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Establece el nombre de la herramienta que creó el PDF.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| producer | string | El nombre del productor. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Establece el trapped.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_trapped | bool | si se establece a <c>true</c> el documento ha sido atrapado. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | El valor al que establecer. |

