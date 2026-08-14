---
title: "XmpBasicPackage‑Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initialisiert eine neue Instanz der [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initialisiert eine neue Instanz der [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Maximaler Bewertungswert. |
| RATING_MIN [static] | int | r | Minimaler Bewertungswert. |
| RATING_REJECTED [static] | int | r | Abgelehnter Bewertungswert. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Setzt das Erstellungswerkzeug. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Setzt den Bezeichner. |
| [set_label(label)](#set_label_label_9) | Setzt das Label. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [set_rating(choise)](#set_rating_choise_14) | Setzt die Bewertung. |
| [set_value(key, value)](#set_value_key_value_15) | Setzt den Wert |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Setzt den XMP-Typwert |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initialisiert eine neue Instanz der [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initialisiert eine neue Instanz der [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prefix | string | Das Präfix. |
| namespace_uri | string | Der Namespace-URI. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| created_date | datetime | Erstellungsdatum. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| created_date | string | Erstellungsdatum. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Setzt das Erstellungswerkzeug.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_tool | string | Name des Werkzeugs. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Setzt den Bezeichner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| idenfifier | string | Der idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Setzt das Label.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Label | string | Das Label. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_date | datetime | Metadaten-Datum. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_date | string | Metadaten-Datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modified_date | datetime | Datum der letzten Änderung. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modified_date | string | Datum der letzten Änderung. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Setzt die Bewertung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Auswahl | int | Von -1 bis 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Setzt den Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt werden soll. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP-Typwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

