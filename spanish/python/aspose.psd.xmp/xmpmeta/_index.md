---
title: "Clase XmpMeta"
type: docs
weight: 410
url: /es/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Inicializa una nueva instancia de la clase [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Inicializa una nueva instancia de la clase [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Obtiene o establece la versión del toolkit Adobe Xmp. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Agrega el atributo. |
| clear_attributes() | Elimina todos los atributos. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Obtiene el atributo. |
| [get_xml_value()](#get_xml_value__3) | Convierte el valor XMP a la representación XML. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Inicializa una nueva instancia de la clase [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Inicializa una nueva instancia de la clase [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| toolkit_version | string | Versión del kit de herramientas Adobe XMP. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Agrega el atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| atributo | string | El atributo. |
| value | string | El valor. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Obtiene el atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| atributo | string | El atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el atributo para el nombre de atributo especificado. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a la representación XML. |


