---
title: "XmpDate"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά την ημερομηνία στο πακέτο XMP."
type: docs
weight: 11
url: /el/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Αναπαριστά την ημερομηνία στο πακέτο XMP.

Μια τιμή ημερομηνίας-ώρας αναπαρίσταται χρησιμοποιώντας ένα υποσύνολο των μορφών όπως ορίζονται στις Μορφές Ημερομηνίας και Ώρας: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Αρχικοποιεί μια νέα παρουσία της κλάσης XmpDate. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης XmpDate. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | Η συμβολοσειρά μορφής ISO 8601 (roundtrip). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Αποκτά τη συμβολοσειρά μορφής για την τρέχουσα τιμή. |
| [getValue()](#getValue--) | Αποκτά ή ορίζει την τιμή της ημερομηνίας. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Επιστρέφει τη συμβολοσειρά που περιέχει την τιμή σε μορφή XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Αποκτά ή ορίζει την τιμή της ημερομηνίας. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης XmpDate.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dateTime | java.util.Date | Μια τιμή ημερομηνίας-ώρας που αναπαρίσταται χρησιμοποιώντας ένα υποσύνολο της μορφοποίησης ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης XmpDate.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dateString | java.lang.String | Η συμβολοσειρά αναπαράστασης της ημερομηνίας. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


Η συμβολοσειρά μορφής ISO 8601 (roundtrip).

Δείτε περισσότερα: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Αποκτά τη συμβολοσειρά μορφής για την τρέχουσα τιμή.

Value: Η συμβολοσειρά μορφής για την τρέχουσα τιμή.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Αποκτά ή ορίζει την τιμή της ημερομηνίας.

Value: Η τιμή της ημερομηνίας.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Επιστρέφει τη συμβολοσειρά που περιέχει την τιμή σε μορφή XMP.

**Returns:**
java.lang.String - Επιστρέφει τη συμβολοσειρά που περιέχει την τιμή σε μορφή XMP.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Αποκτά ή ορίζει την τιμή της ημερομηνίας.

Value: Η τιμή της ημερομηνίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

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

