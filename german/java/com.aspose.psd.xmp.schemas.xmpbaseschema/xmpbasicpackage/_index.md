---
title: "XmpBasicPackage"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt den XMP-Basis-Namespace dar."
type: docs
weight: 10
url: /de/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Stellt den XMP-Basis-Namespace dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initialisiert eine neue Instanz der  XmpBasicPackage  Klasse. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der  XmpBasicPackage  Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RatingMax](#RatingMax) | Bewertung Maximalwert. |
| [RatingMin](#RatingMin) | Bewertung Minimalwert. |
| [RatingRejected](#RatingRejected) | Bewertung abgelehnter Wert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Fügt den Namespace des komplexen Typs hinzu. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Fügt eine Zeichenketten‑Eigenschaft hinzu. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Weist das angegebene XMP-Paket dem aktuellen zu. |
| [clear()](#clear--) | Löscht diese Instanz. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Kombiniert das Paket. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bestimmt, ob der angegebene Schlüssel enthalten ist. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Liest die Schlüssel im XMP-Paket. |
| [getNamespaceUri()](#getNamespaceUri--) | Liest die Namespace-URI. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getXmlNamespace()](#getXmlNamespace--) | Liest den XML-Namespace. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Setzt das Erstellungswerkzeug. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Setzt den Bezeichner. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Setzt das Etikett. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [setRating(int choise)](#setRating-int-) | Setzt die Bewertung. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Setzt den Wert. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Setzt den XMP-Boolean-Wert. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Setzt die XMP-eindeutige Kennung. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Setzt den XMP-Typwert. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initialisiert eine neue Instanz der  XmpBasicPackage  Klasse.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initialisiert eine neue Instanz der  XmpBasicPackage  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Der Namespace-URI. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Bewertung Maximalwert.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Bewertung Minimalwert.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Bewertung abgelehnter Wert.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Fügt den Namespace des komplexen Typs hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typePrefix | java.lang.String | Der Typ-Präfix. |
| typeNamespaceUri | java.lang.String | Der Typ-Namespace-URI. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Fügt eine Zeichenketten‑Eigenschaft hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.String | Der Zeichenkettenwert. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Weist das angegebene XMP-Paket dem aktuellen zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Das XMP-Paket. |

### clear() {#clear--}
```
public void clear()
```


Löscht diese Instanz.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Kombiniert das Paket.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Das andere Paket zum Kombinieren. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Bestimmt, ob der angegebene Schlüssel enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der zu prüfende Schlüssel. |

**Returns:**
boolean - Gibt true zurück, wenn der angegebene Schlüssel den Schlüssel enthält.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Liest die Schlüssel im XMP-Paket.

Wert: Die Schlüssel im XMP-Paket.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Liest die Namespace-URI.

Wert: Der Namespace-URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest das Präfix.

Wert: Das Präfix.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Liest den XML-Namespace.

Wert: Der XML-Namespace.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. Wert: Das Objekt. |

**Returns:**
java.lang.Object - Gibt das Objekt mit dem angegebenen Schlüssel zurück.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Ein  T:System.Collections.Generic.IEnumerator1  der verwendet werden kann, um durch die Sammlung zu iterieren.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Entfernt den Wert mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem entfernten Wert identifiziert wird. |

**Returns:**
boolean - Gibt true zurück, wenn der Wert mit dem angegebenen Schlüssel entfernt wurde.
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createdDate | java.lang.String | Erstellungsdatum. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Erstellungsdatum. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Setzt das Erstellungswerkzeug.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| creatorTool | java.lang.String | Name des Werkzeugs. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Setzt den Bezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| idenfifier | java.lang.String[] | Der idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Setzt das Etikett.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | java.lang.String | Das Etikett. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadaten-Datum. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Metadaten-Datum. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| modifiedDate | java.lang.String | Letztes Änderungsdatum. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Letztes Änderungsdatum. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Setzt die Bewertung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| choise | int | Von -1 bis 5 |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Setzt den Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt werden soll. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Setzt den XMP-Boolean-Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| boolValue | java.lang.String | Der boolesche Wert. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Setzt die XMP-eindeutige Kennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem festgelegten GUID-Wert identifiziert wird. |
| guid | java.lang.String | Der eindeutige Bezeichner. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Setzt den XMP-Typwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Der Wert, auf den gesetzt werden soll. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. Wert: Das Objekt. |
| Wert | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

