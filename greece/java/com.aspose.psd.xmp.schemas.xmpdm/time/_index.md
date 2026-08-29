---
title: "Time"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαράσταση μιας χρονικής τιμής σε δευτερόλεπτα."
type: docs
weight: 13
url: /el/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Αναπαράσταση μιας χρονικής τιμής σε δευτερόλεπτα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Time. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την κλίμακα για την τιμή χρόνου. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή χρόνου στην καθορισμένη κλίμακα. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Λαμβάνει ή ορίζει την κλίμακα για την τιμή χρόνου. |
| [setValue(int value)](#setValue-int-) | Λαμβάνει ή ορίζει την τιμή χρόνου στην καθορισμένη κλίμακα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Time.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | Η κλίμακα. |
| τιμή | int | Η τιμή. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


Λαμβάνει ή ορίζει την κλίμακα για την τιμή χρόνου.

Για NTSC, χρησιμοποιήστε 1001/30000, ή το λιγότερο ακριβές 100/2997. Για PAL, χρησιμοποιήστε 1/25. Τιμή: Η κλίμακα για την τιμή χρόνου.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Λαμβάνει ή ορίζει την τιμή χρόνου στην καθορισμένη κλίμακα.

Τιμή: Η τιμή χρόνου στην καθορισμένη κλίμακα.

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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Λαμβάνει ή ορίζει την κλίμακα για την τιμή χρόνου.

Για NTSC, χρησιμοποιήστε 1001/30000, ή το λιγότερο ακριβές 100/2997. Για PAL, χρησιμοποιήστε 1/25. Τιμή: Η κλίμακα για την τιμή χρόνου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Λαμβάνει ή ορίζει την τιμή χρόνου στην καθορισμένη κλίμακα.

Τιμή: Η τιμή χρόνου στην καθορισμένη κλίμακα.

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

