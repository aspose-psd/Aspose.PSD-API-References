---
title: "ComplexTypeBase"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Repräsentiert die Basisabstraktion für den XMP-Complex-Werttyp."
type: docs
weight: 10
url: /de/java/com.aspose.psd.xmp.types.complex/complextypebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

Repräsentiert die Basisabstraktion für den XMP-Complex-Werttyp.

Siehe mehr: XMP Specification Part 2, Kapitel 1.2.2
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der  ComplexTypeBase  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Fügt den angegebenen Schlüssel hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNamespaceUri()](#getNamespaceUri--) | Liest den Standard-Namespace-URI. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


Initialisiert eine neue Instanz der  ComplexTypeBase  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Der Namespace-URI. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Fügt den angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.Object | Der Wert, zu dem hinzugefügt werden soll. |

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
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Liest den Standard-Namespace-URI.

**Returns:**
java.lang.String - Der Standard-Namespace-URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest das Präfix.

**Returns:**
java.lang.String - Das Präfix.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenkettenwert im XMP-Format.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

