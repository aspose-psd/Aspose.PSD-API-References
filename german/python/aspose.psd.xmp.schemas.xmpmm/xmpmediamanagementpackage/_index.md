---
title: "XmpMediaManagementPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initialisiert eine neue Instanz der XmpMediaManagementPackage Klasse |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Setzt das abgeleitete von. |
| [set_document_id(guid)](#set_document_id_guid_6) | Setzt die Dokumentenkennung. |
| [set_document_id(guid)](#set_document_id_guid_7) | Setzt die Dokumentenkennung. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Setzt die Instanz-ID. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Setzt die Instanz-ID. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Setzt die ursprüngliche Dokumenten-ID. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Setzt die ursprüngliche Dokumenten-ID. |
| [set_value(key, value)](#set_value_key_value_12) | Setzt den Wert |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Setzt den XMP-Typwert |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initialisiert eine neue Instanz der XmpMediaManagementPackage Klasse

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Setzt das abgeleitete von.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Die Ressourcenreferenz |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Setzt die Dokumentenkennung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | Guid | Der eindeutige Bezeichner. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Setzt die Dokumentenkennung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Setzt die Instanz-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | Guid | Der eindeutige Bezeichner. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Setzt die Instanz-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Setzt die ursprüngliche Dokumenten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | Guid | Der eindeutige Bezeichner. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Setzt die ursprüngliche Dokumenten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Setzt den Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem hinzugefügten Wert identifiziert wird |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt werden soll. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP-Typwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

