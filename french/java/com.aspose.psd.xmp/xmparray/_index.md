---
title: "XmpArray"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente Xmp Array dans XmpPackage."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Représente Xmp Array dans  XmpPackage . todo : le tableau peut contenir des données complexes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initialise une nouvelle instance de la classe  XmpArray  . |
| [XmpArray(int type)](#XmpArray-int-) | Initialise une nouvelle instance de la classe  XmpArray  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Ajoute un nouvel élément. |
| [addItem(String item)](#addItem-java.lang.String-) | Ajoute un nouvel élément. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Obtient le tableau des valeurs à l'intérieur de [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Obtient le tableau des valeurs à l'intérieur de  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourne une  System.String  qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initialise une nouvelle instance de la classe  XmpArray  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type du tableau. |
| éléments | java.lang.String[] | La liste des éléments. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initialise une nouvelle instance de la classe  XmpArray  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type du tableau. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Ajoute un nouvel élément.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | L'élément à ajouter à la liste des éléments. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Ajoute un nouvel élément.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| élément | java.lang.String | L'élément à ajouter à la liste des éléments. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient le tableau des valeurs à l'intérieur de [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Obtient le tableau des valeurs à l'intérieur de  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
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


Retourne une  System.String  qui représente cette instance.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

