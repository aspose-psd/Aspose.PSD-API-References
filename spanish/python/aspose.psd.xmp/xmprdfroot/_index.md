---
title: "Clase XmpRdfRoot"
type: docs
weight: 460
url: /es/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Inicializa una nueva instancia de la clase XmpRdfRoot |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Agrega el atributo. |
| clear_attributes() | Elimina todos los atributos. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Obtiene el atributo. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Obtiene el URI del espacio de nombres mediante un prefijo específico. El prefijo puede comenzar sin xmlns. |
| [get_xml_value()](#get_xml_value__4) | Convierte el valor xmp a la representación xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Agrega el URI del espacio de nombres mediante un prefijo. El prefijo puede comenzar sin xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Inicializa una nueva instancia de la clase XmpRdfRoot

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


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Obtiene el URI del espacio de nombres mediante un prefijo específico. El prefijo puede comenzar sin xmlns.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefijo | string | El prefijo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve un URI de esquema de paquete. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Convierte el valor xmp a la representación xml.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a una cadena XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Agrega el URI del espacio de nombres mediante un prefijo. El prefijo puede comenzar sin xmlns.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefijo | string | El prefijo. |
| namespace_uri | string | URI del esquema del paquete. |

