---
title: "XmpRightsManagementPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initialisiert eine neue Instanz der XmpRightsManagementPackage-Klasse |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Setzt das Zertifikat |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Markiert als Rechte-Management-Inhalt |
| [set_owners(owners)](#set_owners_owners_7) | Setzt Eigentümer |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Setzt die Nutzungsbedingungen |
| [set_value(key, value)](#set_value_key_value_9) | Setzt den Wert |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Setzt die Web-Erklärung |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Setzt den XMP-Typwert |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initialisiert eine neue Instanz der XmpRightsManagementPackage-Klasse

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Setzt das Zertifikat

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zertifikat | string | Das Zertifikat. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Markiert als Rechte-Management-Inhalt

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | bool | wenn auf <c>true</c> gesetzt, dass dies eine rights‑managed Ressource ist. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Setzt Eigentümer

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Eigentümer | string | Die Eigentümer. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Setzt die Nutzungsbedingungen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Die Nutzungsbedingungen. |

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

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Setzt die Web-Erklärung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| web_statement_url | string | Die Web-Statement-URL. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP-Typwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

