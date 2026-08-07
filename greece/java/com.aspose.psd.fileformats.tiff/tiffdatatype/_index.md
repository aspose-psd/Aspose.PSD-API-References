---
title: "TiffDataType"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο τύπος δεδομένων tiff."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Ο τύπος δεδομένων tiff.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Συγκρίνει την τρέχουσα παρουσία με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει εάν η τρέχουσα παρουσία προηγείται, ακολουθεί ή βρίσκεται στην ίδια θέση στη σειρά ταξινόμησης με το άλλο αντικείμενο. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα βαθύ κλώνο αυτής της παρουσίας. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων. |
| [getDataSize()](#getDataSize--) | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| [getId()](#getId--) | Λαμβάνει την ακέραια αναπαράσταση του αναγνωριστικού ετικέτας. |
| [getTagId()](#getTagId--) | Λαμβάνει το αναγνωριστικό της ετικέτας. |
| [getTagType()](#getTagType--) | Λαμβάνει τον τύπο της ετικέτας. |
| [getValue()](#getValue--) | Λαμβάνει την τιμή που περιέχει αυτός ο τύπος δεδομένων. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ετικέτα είναι ιδιωτική. |
| [isValid()](#isValid--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της ετικέτας είναι έγκυρα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Διαβάζει τα δεδομένα της ετικέτας. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ορίζει την τιμή που περιέχει αυτός ο τύπος δεδομένων. |
| [toString()](#toString--) | Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Γράφει τα πρόσθετα δεδομένα της ετικέτας. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Γράφει τα δεδομένα της ετικέτας. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Συγκρίνει την τρέχουσα παρουσία με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει εάν η τρέχουσα παρουσία προηγείται, ακολουθεί ή βρίσκεται στην ίδια θέση στη σειρά ταξινόμησης με το άλλο αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Ένα αντικείμενο για σύγκριση με αυτήν την παρουσία. |

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος που υποδεικνύει τη σχετική σειρά των αντικειμένων που συγκρίνονται. Η τιμή επιστροφής έχει τις εξής σημασίες: Τιμή Σημασία Μικρότερο του μηδενός Αυτή η παρουσία είναι μικρότερη από το obj. Μηδέν Αυτή η παρουσία είναι ίση με το obj. Μεγαλύτερο του μηδενός Αυτή η παρουσία είναι μεγαλύτερη από το obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Δημιουργεί ένα βαθύ κλώνο αυτής της παρουσίας.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας).

**Returns:**
long - Το πρόσθετο μέγεθος δεδομένων σε bytes.

Αυτή είναι η καταμέτρηση των bytes δεδομένων ευθυγραμμισμένη στο όριο λέξης.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Λαμβάνει τον αριθμό των στοιχείων.

**Returns:**
long - Ο αριθμός των στοιχείων.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας).

**Returns:**
long - Το πρόσθετο μέγεθος δεδομένων σε bytes.

Αυτή είναι η ακριβής καταμέτρηση των bytes.
### getId() {#getId--}
```
public int getId()
```


Λαμβάνει την ακέραια αναπαράσταση του αναγνωριστικού ετικέτας.

**Returns:**
int - Η ακέραια αναπαράσταση του αναγνωριστικού ετικέτας
### getTagId() {#getTagId--}
```
public int getTagId()
```


Λαμβάνει το αναγνωριστικό της ετικέτας.

**Returns:**
int - Το αναγνωριστικό ετικέτας.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Λαμβάνει τον τύπο της ετικέτας.

**Returns:**
int - Ο τύπος ετικέτας.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Λαμβάνει την τιμή που περιέχει αυτός ο τύπος δεδομένων.

**Returns:**
java.lang.Object - Η τιμή.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ετικέτα είναι ιδιωτική. Οι ιδιωτικές tiff ετικέτες είναι ετικέτες με αναγνωριστικό ετικέτας πάνω από 32768.

**Returns:**
boolean -  true  εάν τα δεδομένα ετικέτας είναι έγκυρα· διαφορετικά,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της ετικέτας είναι έγκυρα. Η έγκυρη ετικέτα περιέχει δεδομένα που μπορούν να διατηρηθούν. Η μη έγκυρη ετικέτα δεν μπορεί να αποθηκευτεί.

**Returns:**
boolean -  true  εάν τα δεδομένα ετικέτας είναι έγκυρα· διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Διαβάζει τα δεδομένα της ετικέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Η ροή δεδομένων. |
| position | long | Η θέση της ετικέτας. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Ορίζει την τιμή που περιέχει αυτός ο τύπος δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | Η τιμή. |

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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Γράφει τα πρόσθετα δεδομένα της ετικέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Η ροή δεδομένων. |

**Returns:**
long - Τα πραγματικά bytes που γράφτηκαν.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Γράφει τα δεδομένα της ετικέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Η ροή δεδομένων. |
| additionalDataOffset | long | Η μετατόπιση για την εγγραφή πρόσθετων δεδομένων. |

