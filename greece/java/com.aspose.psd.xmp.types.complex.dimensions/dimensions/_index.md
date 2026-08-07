---
title: "Διαστάσεις"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο."
type: docs
weight: 10
url: /el/java/com.aspose.psd.xmp.types.complex.dimensions/dimensions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Dimensions extends ComplexTypeBase
```

Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Dimensions()](#Dimensions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  Dimensions  . |
| [Dimensions(float width, float height)](#Dimensions-float-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  Dimensions  . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Προσθέτει το καθορισμένο κλειδί. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος. |
| [getNamespaceUri()](#getNamespaceUri--) | Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων. |
| [getPrefix()](#getPrefix--) | Ανακτά το πρόθεμα. |
| [getUnits()](#getUnits--) | Λαμβάνει ή ορίζει τις μονάδες. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHeight(float value)](#setHeight-float-) | Λαμβάνει ή ορίζει το ύψος. |
| [setUnits(String value)](#setUnits-java.lang.String-) | Λαμβάνει ή ορίζει τις μονάδες. |
| [setWidth(float value)](#setWidth-float-) | Λαμβάνει ή ορίζει το πλάτος. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Dimensions() {#Dimensions--}
```
public Dimensions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  Dimensions  .

### Dimensions(float width, float height) {#Dimensions-float-float-}
```
public Dimensions(float width, float height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  Dimensions  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | float | Το πλάτος. |
| ύψος | float | Το ύψος. |

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
public float getHeight()
```


Λαμβάνει ή ορίζει το ύψος.

**Returns:**
float
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
### getUnits() {#getUnits--}
```
public String getUnits()
```


Λαμβάνει ή ορίζει τις μονάδες.

Για παράδειγμα: ίντσα, mm, pixel, pica, point κλπ. Τιμή: Οι μονάδες.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public float getWidth()
```


Λαμβάνει ή ορίζει το πλάτος.

**Returns:**
float
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




### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Λαμβάνει ή ορίζει το ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setUnits(String value) {#setUnits-java.lang.String-}
```
public void setUnits(String value)
```


Λαμβάνει ή ορίζει τις μονάδες.

Για παράδειγμα: ίντσα, mm, pixel, pica, point κλπ. Τιμή: Οι μονάδες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Λαμβάνει ή ορίζει το πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

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

