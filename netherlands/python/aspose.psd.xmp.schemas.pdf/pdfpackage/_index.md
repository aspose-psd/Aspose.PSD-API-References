---
title: "PdfPackage-klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initialiseert een nieuw exemplaar van de PdfPackage-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Haalt de namespace-URI op. |
| voorvoegsel | string | r | Haalt het voorvoegsel op. |
| xml_namespace | string | r | Haalt de XML-namespace op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Voegt een stringeigenschap toe. |
| clear() | Maakt deze instantie leeg. |
| [contains_key(key)](#contains_key_key_2) | Bepaalt of de opgegeven sleutel de sleutel bevat. |
| [get_xml_value()](#get_xml_value__3) | Converteert XMP-waarde naar de XML-representatie. |
| [remove(key)](#remove_key_4) | Verwijder de waarde met de opgegeven sleutel. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Stelt de trefwoorden in. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Stelt de PDF-versie in. |
| [set_producer(producer)](#set_producer_producer_7) | Stelt de naam van de tool in die de Pdf heeft gemaakt. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Stelt de trapped in. |
| [set_value(key, value)](#set_value_key_value_9) | Stelt de waarde in. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Stelt de XMP-typewaarde in. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initialiseert een nieuw exemplaar van de PdfPackage-klasse

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Voegt een stringeigenschap toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | string | De tekenreekswaarde. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Bepaalt of de opgegeven sleutel de sleutel bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De te controleren sleutel. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert true als de opgegeven sleutel de sleutel bevat. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converteert XMP-waarde naar de XML-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de XMP-waarde geconverteerd naar de XML-representatie. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Verwijder de waarde met de opgegeven sleutel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de verwijderde waarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert true als de waarde met de opgegeven sleutel is verwijderd. |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Stelt de trefwoorden in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| trefwoorden | string | De trefwoorden. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Stelt de PDF-versie in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| version | string | Pdf-versie, bijvoorbeeld: 1.0, 1.3 enz. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Stelt de naam van de tool in die de Pdf heeft gemaakt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| producent | string | De naam van de producent. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Stelt de trapped in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| is_trapped | bool | indien ingesteld op <c>true</c> is het document trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Stelt de waarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Stelt de XMP-typewaarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | De waarde om in te stellen. |

