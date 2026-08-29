---
title: "PdfPackage‑klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initierar en ny instans av PdfPackage-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Hämtar namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| xml_namespace | string | r | Hämtar XML‑namnrymden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Lägger till en strängegenskap. |
| clear() | Rensar denna instans. |
| [contains_key(key)](#contains_key_key_2) | Bestämmer om den angivna nyckeln innehåller nyckeln. |
| [get_xml_value()](#get_xml_value__3) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_4) | Tar bort värdet med den angivna nyckeln. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Ställer in nyckelorden. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Ställer in PDF-versionen. |
| [set_producer(producer)](#set_producer_producer_7) | Ställer in namnet på verktyget som skapade Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Ställer in trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Ställer in värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Ställer in XMP‑typvärdet. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initierar en ny instans av PdfPackage-klassen

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till en strängegenskap.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| värde | string | Strängvärdet. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Bestämmer om den angivna nyckeln innehåller nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Nyckeln som ska kontrolleras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om den angivna nyckeln innehåller nyckeln. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP-värdet konverterat till XML-representationen. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Tar bort värdet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om värdet med den angivna nyckeln togs bort. |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Ställer in nyckelorden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckelord | string | Nyckelorden. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Ställer in PDF-versionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| version | string | Pdf-version, till exempel: 1.0, 1.3 osv. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Ställer in namnet på verktyget som skapade Pdf.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| producent | string | Producentens namn. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Ställer in trapped.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_trapped | bool | Om den är inställd på <c>true</c> har dokumentet blivit trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Ställer in värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Ställer in XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Värdet att sätta till. |

