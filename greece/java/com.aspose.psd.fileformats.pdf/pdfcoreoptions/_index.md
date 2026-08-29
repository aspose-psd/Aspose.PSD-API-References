---
title: "PdfCoreOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι κοινές επιλογές για μετατροπή σε PDF."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.pdf/pdfcoreoptions/
---

**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Οι κοινές επιλογές για μετατροπή σε PDF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Καθορίζει σε ποιο επίπεδο του περιγράμματος του εγγράφου θα εμφανίζονται τα αντικείμενα σελιδοδεικτών. |
| [getClass()](#getClass--) |  |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Καθορίζει πόσα επίπεδα του περιγράμματος του εγγράφου θα εμφανίζονται αναπτυγμένα όταν προβάλλεται το αρχείο PDF. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Καθορίζει πόσα επίπεδα στοιχείων περιγράμματος θα συμπεριληφθούν στο περίγραμμα του εγγράφου. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα της συμπίεσης JPEG για εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). |
| [getPdfCompliance()](#getPdfCompliance--) | Αποκτά τη συμμόρφωση PDF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Καθορίζει σε ποιο επίπεδο του περιγράμματος του εγγράφου θα εμφανίζονται τα αντικείμενα σελιδοδεικτών. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Καθορίζει πόσα επίπεδα του περιγράμματος του εγγράφου θα εμφανίζονται αναπτυγμένα όταν προβάλλεται το αρχείο PDF. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Καθορίζει πόσα επίπεδα στοιχείων περιγράμματος θα συμπεριληφθούν στο περίγραμμα του εγγράφου. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα της συμπίεσης JPEG για εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Ορίζει τη συμμόρφωση PDF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


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
### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Καθορίζει σε ποιο επίπεδο του περιγράμματος του εγγράφου θα εμφανίζονται τα αντικείμενα σελιδοδεικτών. 0 - δεν εμφανίζεται. 1 στο πρώτο επίπεδο κ.ο.κ. Η προεπιλογή είναι 0.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Καθορίζει πόσα επίπεδα του περιγράμματος του εγγράφου θα εμφανίζονται αναπτυγμένα όταν προβάλλεται το αρχείο PDF. 0 - το περίγραμμα του εγγράφου δεν είναι αναπτυγμένο. 1 - τα στοιχεία του πρώτου επιπέδου στο έγγραφο είναι αναπτυγμένα κ.ο.κ. Η προεπιλογή είναι 0.

**Returns:**
int
### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Καθορίζει πόσα επίπεδα στοιχείων περιγράμματος θα συμπεριληφθούν στο περίγραμμα του εγγράφου. 0 - χωρίς περίγραμμα, 1 - ένα επίπεδο περιγράμματος κ.ο.κ. Η προεπιλογή είναι 0.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Καθορίζει την ποιότητα της συμπίεσης JPEG για εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). Η προεπιλογή είναι 95.

**Returns:**
int
### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Αποκτά τη συμμόρφωση PDF.

**Returns:**
int - η συμμόρφωση PDF.
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




### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Καθορίζει σε ποιο επίπεδο του περιγράμματος του εγγράφου θα εμφανίζονται τα αντικείμενα σελιδοδεικτών. 0 - δεν εμφανίζεται. 1 στο πρώτο επίπεδο κ.ο.κ. Η προεπιλογή είναι 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Καθορίζει πόσα επίπεδα του περιγράμματος του εγγράφου θα εμφανίζονται αναπτυγμένα όταν προβάλλεται το αρχείο PDF. 0 - το περίγραμμα του εγγράφου δεν είναι αναπτυγμένο. 1 - τα στοιχεία του πρώτου επιπέδου στο έγγραφο είναι αναπτυγμένα κ.ο.κ. Η προεπιλογή είναι 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Καθορίζει πόσα επίπεδα στοιχείων περιγράμματος θα συμπεριληφθούν στο περίγραμμα του εγγράφου. 0 - χωρίς περίγραμμα, 1 - ένα επίπεδο περιγράμματος κ.ο.κ. Η προεπιλογή είναι 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Καθορίζει την ποιότητα της συμπίεσης JPEG για εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). Η προεπιλογή είναι 95.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Ορίζει τη συμμόρφωση PDF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | η συμμόρφωση PDF. |

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

