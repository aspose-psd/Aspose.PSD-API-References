---
title: "XmpArray"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt Xmp Array voor in XmpPackage."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Stelt Xmp Array voor in XmpPackage. todo: Array kan complexe gegevens bevatten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initialiseert een nieuw exemplaar van de XmpArray-klasse. |
| [XmpArray(int type)](#XmpArray-int-) | Initialiseert een nieuw exemplaar van de XmpArray-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Voegt nieuw item toe. |
| [addItem(String item)](#addItem-java.lang.String-) | Voegt nieuw item toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Haalt array van waarden op binnen [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Haalt array van waarden op binnen XmpArray. |
| [getXmlValue()](#getXmlValue--) | Converteert XMP-waarde naar de XML-representatie. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een  System.String  die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initialiseert een nieuw exemplaar van de XmpArray-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type van de array. |
| items | java.lang.String[] | De lijst met items. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initialiseert een nieuw exemplaar van de XmpArray-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type van de array. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Voegt nieuw item toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Het element dat aan de lijst met items moet worden toegevoegd. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Voegt nieuw item toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | java.lang.String | Het item dat aan de lijst met items moet worden toegevoegd. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt array van waarden op binnen [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Haalt array van waarden op binnen XmpArray.

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converteert XMP-waarde naar de XML-representatie.

**Returns:**
java.lang.String - Retourneert de XMP-waarde geconverteerd naar de XML-representatie.
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


Retourneert een  System.String  die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

