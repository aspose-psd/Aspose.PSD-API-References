---
title: "PdfPackage-Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initialisiert eine neue Instanz der PdfPackage-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Gibt die Namespace-URI zurück |
| prefix | string | r | Liest das Präfix. |
| xml_namespace | string | r | Gibt den XML-Namespace zurück |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Fügt eine String-Eigenschaft hinzu |
| clear() | Löscht diese Instanz |
| [contains_key(key)](#contains_key_key_2) | Bestimmt, ob der angegebene Schlüssel den Schlüssel enthält |
| [get_xml_value()](#get_xml_value__3) | Konvertiert den XMP-Wert in die XML-Darstellung |
| [remove(key)](#remove_key_4) | Entfernt den Wert mit dem angegebenen Schlüssel |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Setzt die Schlüsselwörter. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Setzt die PDF-Version. |
| [set_producer(producer)](#set_producer_producer_7) | Setzt den Namen des Werkzeugs, das das Pdf erstellt hat. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Setzt das trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Setzt den Wert |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Setzt den XMP-Typwert |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initialisiert eine neue Instanz der PdfPackage-Klasse

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Fügt eine String-Eigenschaft hinzu

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| Wert | string | Der Zeichenkettenwert |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Bestimmt, ob der angegebene Schlüssel den Schlüssel enthält

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Der zu prüfende Schlüssel |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn der angegebene Schlüssel den Schlüssel enthält |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Entfernt den Wert mit dem angegebenen Schlüssel

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem entfernten Wert identifiziert wird |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn der Wert mit dem angegebenen Schlüssel entfernt wurde |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Setzt die Schlüsselwörter.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüsselwörter | string | Die Schlüsselwörter. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Setzt die PDF-Version.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| version | string | Pdf-Version, zum Beispiel: 1.0, 1.3 usw. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Setzt den Namen des Werkzeugs, das das Pdf erstellt hat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Ersteller | string | Der Produzentenname. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Setzt das trapped.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_trapped | bool | Wenn auf <c>true</c> gesetzt, ist das Dokument gefangen. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Setzt den Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt werden soll. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP-Typwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

