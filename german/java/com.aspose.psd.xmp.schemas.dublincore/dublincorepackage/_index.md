---
title: "DublinCorePackage"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt das Dublic-Core-Schema dar."
type: docs
weight: 10
url: /de/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Stellt das Dublic-Core-Schema dar.

Weitere Informationen finden Sie unter: http://dublincore.org/documents/usageguide/elements.shtml.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | Initialisiert eine neue Instanz der  DublinCorePackage  Klasse. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Liest oder setzt das  Object  mit dem angegebenen Schlüssel. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Fügt den Autor hinzu. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | Fügt den Autor hinzu. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | Fügt die Beschreibung hinzu. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | Fügt die Beschreibung hinzu. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Fügt den Verlag hinzu. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | Fügt den Verlag hinzu. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Fügt das Thema hinzu. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | Fügt das Thema hinzu. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | Fügt Dublin-Core-Titel für verschiedene Sprachen hinzu. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Fügt Dublin-Core-Titel hinzu. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Setzt den Wert. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Setzt den XMP-Boolean-Wert. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Setzt die XMP-eindeutige Kennung. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Setzt den XMP-Typwert. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Setzt das  Objekt  mit dem angegebenen Schlüssel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


Initialisiert eine neue Instanz der  DublinCorePackage  Klasse.

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


Liest oder setzt das  Object  mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. |

**Returns:**
java.lang.Object - Gibt das  Objekt  mit dem angegebenen Schlüssel zurück.
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
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Fügt den Autor hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Autor | java.lang.String | Der Autor. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


Fügt den Autor hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Autor | java.lang.String[] | Der Autor. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


Fügt die Beschreibung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | Die Beschreibung. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


Fügt die Beschreibung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| desc | java.lang.String | Die Beschreibung. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


Fügt den Verlag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Verlag | java.lang.String | Der Verlag. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


Fügt den Verlag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Verlag | java.lang.String[] | Der Verlag. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


Fügt das Thema hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Betreff | java.lang.String | Der Betreff. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


Fügt das Thema hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Betreff | java.lang.String[] | Der Betreff. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


Fügt Dublin-Core-Titel für verschiedene Sprachen hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | Instanz von  LangAlt . |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Fügt Dublin-Core-Titel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Titel | java.lang.String | Der Titel. |

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


Setzt das  Objekt  mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. |
| Wert | java.lang.Object | Der  Objekt  Wert. |

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

