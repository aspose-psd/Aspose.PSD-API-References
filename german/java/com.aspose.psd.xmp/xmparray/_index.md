---
title: "XmpArray"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt Xmp Array in XmpPackage dar."
type: docs
weight: 12
url: /de/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Stellt Xmp Array in  XmpPackage dar. todo: Array kann komplexe Daten enthalten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initialisiert eine neue Instanz der  XmpArray  Klasse. |
| [XmpArray(int type)](#XmpArray-int-) | Initialisiert eine neue Instanz der  XmpArray  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Fügt ein neues Element hinzu. |
| [addItem(String item)](#addItem-java.lang.String-) | Fügt ein neues Element hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Liefert ein Array von Werten innerhalb von [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Liefert ein Array von Werten innerhalb von  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt einen  System.String  zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initialisiert eine neue Instanz der  XmpArray  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Der Typ des Arrays. |
| items | java.lang.String[] | Die Elementliste. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initialisiert eine neue Instanz der  XmpArray  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Der Typ des Arrays. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Fügt ein neues Element hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Fügt ein neues Element hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element | java.lang.String | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


Liefert ein Array von Werten innerhalb von [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Liefert ein Array von Werten innerhalb von  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
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


Gibt einen  System.String  zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
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

