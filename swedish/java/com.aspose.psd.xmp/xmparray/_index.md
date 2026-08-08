---
title: "XmpArray"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar Xmp Array i XmpPackage."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Representerar Xmp Array i  XmpPackage . todo: Array kan innehålla komplex data.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initierar en ny instans av  XmpArray  klassen. |
| [XmpArray(int type)](#XmpArray-int-) | Initierar en ny instans av  XmpArray  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Lägger till ett nytt objekt. |
| [addItem(String item)](#addItem-java.lang.String-) | Lägger till ett nytt objekt. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Hämtar en array av värden inuti [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Hämtar en array av värden inuti  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP‑värdet till XML‑representationen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en  System.String  som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initierar en ny instans av  XmpArray  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typen av array. |
| objekt | java.lang.String[] | Listan med objekt. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initierar en ny instans av  XmpArray  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typen av array. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Lägger till ett nytt objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Elementet som ska läggas till i listan med objekt. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Lägger till ett nytt objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | java.lang.String | Objektet som ska läggas till i listan med objekt. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar en array av värden inuti [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Hämtar en array av värden inuti  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP‑värdet till XML‑representationen.

**Returns:**
java.lang.String - Returnerar XMP-värdet konverterat till XML-representationen.
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


Returnerar en  System.String  som representerar detta objekt.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

