---
title: "Classe XmpMeta"
type: docs
weight: 410
url: /it/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Inizializza una nuova istanza della classe [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Inizializza una nuova istanza della classe [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Ottiene o imposta la versione del toolkit Adobe Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Aggiunge l'attributo. |
| clear_attributes() | Rimuove tutti gli attributi. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Ottiene l'attributo. |
| [get_xml_value()](#get_xml_value__3) | Converte il valore XMP nella rappresentazione XML. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Inizializza una nuova istanza della classe [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Inizializza una nuova istanza della classe [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| toolkit_version | string | Versione del toolkit Adobe XMP. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Aggiunge l'attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attributo | string | L'attributo. |
| value | string | Il valore. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Ottiene l'attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attributo | string | L'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce l'attributo per il nome attributo specificato. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converte il valore XMP nella rappresentazione XML.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito nella rappresentazione XML. |


