---
title: "XmpArray"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει το Xmp Array στο XmpPackage."
type: docs
weight: 12
url: /el/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Αντιπροσωπεύει το Xmp Array στο  XmpPackage . todo: Το Array μπορεί να περιέχει σύνθετα δεδομένα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Αρχικοποιεί μια νέα παρουσία της  XmpArray  κλάσης. |
| [XmpArray(int type)](#XmpArray-int-) | Αρχικοποιεί μια νέα παρουσία της  XmpArray  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Προσθέτει νέο στοιχείο. |
| [addItem(String item)](#addItem-java.lang.String-) | Προσθέτει νέο στοιχείο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Λαμβάνει τον πίνακα τιμών μέσα στο [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Λαμβάνει τον πίνακα τιμών μέσα στο  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Αρχικοποιεί μια νέα παρουσία της  XmpArray  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ο τύπος του πίνακα. |
| στοιχεία | java.lang.String[] | Η λίστα στοιχείων. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Αρχικοποιεί μια νέα παρουσία της  XmpArray  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ο τύπος του πίνακα. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Προσθέτει νέο στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Το στοιχείο που θα προστεθεί στη λίστα των στοιχείων. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Προσθέτει νέο στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στοιχείο | java.lang.String | Το στοιχείο που θα προστεθεί στη λίστα των στοιχείων. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Λαμβάνει τον πίνακα τιμών μέσα στο [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Λαμβάνει τον πίνακα τιμών μέσα στο  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns:**
java.lang.String - Επιστρέφει την τιμή XMP μετατρεπόμενη στην αναπαράσταση XML.
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


Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.

**Returns:**
java.lang.String - Ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

