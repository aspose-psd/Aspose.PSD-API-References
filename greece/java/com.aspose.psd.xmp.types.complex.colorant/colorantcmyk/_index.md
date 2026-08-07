---
title: "ColorantCmyk"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει το CMYK Colorant."
type: docs
weight: 13
url: /el/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Αντιπροσωπεύει το CMYK Colorant.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Αρχικοποιεί ένα νέο αντικείμενο της  ColorantCmyk  κλάσης. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Αρχικοποιεί ένα νέο αντικείμενο της  ColorantCmyk  κλάσης. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Μέγιστη τιμή χρώματος σε χρωστικό CMYK. |
| [ColorValueMin](#ColorValueMin) | Ελάχιστη τιμή χρώματος σε χρωστικό CMYK. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Προσθέτει το καθορισμένο κλειδί. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Λαμβάνει ή ορίζει την τιμή του μαύρου συστατικού. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Λαμβάνει ή ορίζει τον τύπο του χρώματος. |
| [getCyan()](#getCyan--) | Λαμβάνει ή ορίζει την τιμή του κυανίου συστατικού. |
| [getMagenta()](#getMagenta--) | Λαμβάνει ή ορίζει την τιμή του ματζέντα συστατικού. |
| [getMode()](#getMode--) | Λαμβάνει  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων. |
| [getPrefix()](#getPrefix--) | Ανακτά το πρόθεμα. |
| [getSwatchName()](#getSwatchName--) | Λαμβάνει ή ορίζει το όνομα του δείγματος. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP. |
| [getYellow()](#getYellow--) | Λαμβάνει ή ορίζει την τιμή του κίτρινου συστατικού. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Λαμβάνει ή ορίζει την τιμή του μαύρου συστατικού. |
| [setColorType(int value)](#setColorType-int-) | Λαμβάνει ή ορίζει τον τύπο του χρώματος. |
| [setCyan(float value)](#setCyan-float-) | Λαμβάνει ή ορίζει την τιμή του κυανίου συστατικού. |
| [setMagenta(float value)](#setMagenta-float-) | Λαμβάνει ή ορίζει την τιμή του ματζέντα συστατικού. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του δείγματος. |
| [setYellow(float value)](#setYellow-float-) | Λαμβάνει ή ορίζει την τιμή του κίτρινου συστατικού. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Αρχικοποιεί ένα νέο αντικείμενο της  ColorantCmyk  κλάσης.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Αρχικοποιεί ένα νέο αντικείμενο της  ColorantCmyk  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μαύρο | float | Η τιμή του μαύρου συστατικού. |
| κυανό | float | Η τιμή του συστατικού του κυανό χρώματος. |
| ματζέντα | float | Η τιμή του συστατικού ματζέντα. |
| κίτρινο | float | Η τιμή του κίτρινου συστατικού. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Μέγιστη τιμή χρώματος σε χρωστικό CMYK.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Ελάχιστη τιμή χρώματος σε χρωστικό CMYK.

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Λαμβάνει ή ορίζει την τιμή του μαύρου συστατικού.

Τιμή: Η τιμή του μαύρου συστατικού.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Λαμβάνει ή ορίζει τον τύπο του χρώματος.

Τιμή: Ο τύπος του χρώματος.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Λαμβάνει ή ορίζει την τιμή του κυανίου συστατικού.

Τιμή: Η τιμή του κυανό συστατικού.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Λαμβάνει ή ορίζει την τιμή του ματζέντα συστατικού.

Τιμή: Η τιμή του ματζέντα συστατικού.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Λαμβάνει  ColorMode .

Τιμή: Η λειτουργία χρώματος.

**Returns:**
int
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
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Λαμβάνει ή ορίζει το όνομα του δείγματος.

Τιμή: Το όνομα του δείγματος.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP.

**Returns:**
java.lang.String - Επιστρέφει την τιμή συμβολοσειράς σε μορφή XMP.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Λαμβάνει ή ορίζει την τιμή του κίτρινου συστατικού.

Τιμή: Η τιμή του κίτρινου συστατικού.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Λαμβάνει ή ορίζει την τιμή του μαύρου συστατικού.

Τιμή: Η τιμή του μαύρου συστατικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του χρώματος.

Τιμή: Ο τύπος του χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Λαμβάνει ή ορίζει την τιμή του κυανίου συστατικού.

Τιμή: Η τιμή του κυανό συστατικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Λαμβάνει ή ορίζει την τιμή του ματζέντα συστατικού.

Τιμή: Η τιμή του ματζέντα συστατικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Λαμβάνει ή ορίζει το όνομα του δείγματος.

Τιμή: Το όνομα του δείγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Λαμβάνει ή ορίζει την τιμή του κίτρινου συστατικού.

Τιμή: Η τιμή του κίτρινου συστατικού.

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

