---
title: "XmpPackage Klasse"
type: docs
weight: 430
url: /de/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Gibt die Namespace-URI zurück |
| prefix | string | r | Liest das Präfix. |
| xml_namespace | string | r | Gibt den XML-Namespace zurück |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Fügt den Wert hinzu. |
| clear() | Löscht diese Instanz |
| [contains_key(key)](#contains_key_key_2) | Bestimmt, ob der angegebene Schlüssel den Schlüssel enthält |
| [get_xml_value()](#get_xml_value__3) | Konvertiert den XMP-Wert in die XML-Darstellung |
| [remove(key)](#remove_key_4) | Entfernt den Wert mit dem angegebenen Schlüssel |
| [set_value(key, value)](#set_value_key_value_5) | Setzt den Wert |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Setzt den XMP-Typwert |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Fügt den Wert hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| Wert | string | Der Wert, zu dem hinzugefügt werden soll. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Setzt den Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt werden soll. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP-Typwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

