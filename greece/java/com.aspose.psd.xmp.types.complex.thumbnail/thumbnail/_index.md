---
title: "Thumbnail"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά την μικρογραφία εικόνας για ένα αρχείο."
type: docs
weight: 10
url: /el/java/com.aspose.psd.xmp.types.complex.thumbnail/thumbnail/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Thumbnail extends ComplexTypeBase
```

Αναπαριστά την μικρογραφία εικόνας για ένα αρχείο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Thumbnail()](#Thumbnail--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Thumbnail . |
| [Thumbnail(int width, int height)](#Thumbnail-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Thumbnail . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Προσθέτει το καθορισμένο κλειδί. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος. |
| [getImageBase64()](#getImageBase64--) | Λαμβάνει ή ορίζει την εικόνα σε μορφή base64. |
| [getNamespaceUri()](#getNamespaceUri--) | Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων. |
| [getPrefix()](#getPrefix--) | Ανακτά το πρόθεμα. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHeight(int value)](#setHeight-int-) | Λαμβάνει ή ορίζει το ύψος. |
| [setImageBase64(String value)](#setImageBase64-java.lang.String-) | Λαμβάνει ή ορίζει την εικόνα σε μορφή base64. |
| [setWidth(int value)](#setWidth-int-) | Λαμβάνει ή ορίζει το πλάτος. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail() {#Thumbnail--}
```
public Thumbnail()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Thumbnail .

### Thumbnail(int width, int height) {#Thumbnail-int-int-}
```
public Thumbnail(int width, int height)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Thumbnail .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Προσθέτει το καθορισμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| τιμή | java.lang.Object | Η τιμή προς προσθήκη. |

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
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λαμβάνει ή ορίζει το ύψος.

**Returns:**
int
### getImageBase64() {#getImageBase64--}
```
public String getImageBase64()
```


Λαμβάνει ή ορίζει την εικόνα σε μορφή base64.

Τιμή: Η εικόνα σε μορφή base64.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων.

**Returns:**
java.lang.String - Η προεπιλεγμένη διεύθυνση URI του ονοματοχώρου.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ανακτά το πρόθεμα.

**Returns:**
java.lang.String - Το πρόθεμα.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει ή ορίζει το πλάτος.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP.

**Returns:**
java.lang.String - Επιστρέφει την τιμή συμβολοσειράς σε μορφή XMP.
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




### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Λαμβάνει ή ορίζει το ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setImageBase64(String value) {#setImageBase64-java.lang.String-}
```
public void setImageBase64(String value)
```


Λαμβάνει ή ορίζει την εικόνα σε μορφή base64.

Τιμή: Η εικόνα σε μορφή base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Λαμβάνει ή ορίζει το πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

