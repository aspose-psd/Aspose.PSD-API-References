---
title: "TiffSRational"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο λογικός τύπος tiff."
type: docs
weight: 13
url: /el/java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Ο λογικός τύπος tiff.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffSRational . |
| [TiffSRational(int value)](#TiffSRational-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffRational  class. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffSRational . |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Epsilon](#Epsilon) | Το epsilon για τον υπολογισμό του κλάσματος |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα. |
| [approximateFraction(float value)](#approximateFraction-float-) | Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο  Object  είναι ίσο με αυτήν την παρουσία. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Λαμβάνει τον παρονομαστή. |
| [getNominator()](#getNominator--) | Λαμβάνει τον αριθμητή. |
| [getValue()](#getValue--) | Λαμβάνει την τιμή float. |
| [getValueD()](#getValueD--) | Λαμβάνει τη διπλή τιμή. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffSRational .

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffRational  class.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η τιμή του αριθμητή. |

Ο αριθμητής θα χρησιμοποιηθεί ως η καθορισμένη τιμή και ο παρονομαστής θα είναι ίσος με 1. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  TiffSRational .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριθμητής | int | Ο αριθμητής. |
| παρονομαστής | int | Ο παρονομαστής. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Το epsilon για τον υπολογισμό του κλάσματος

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Η τιμή. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Η τιμή. |
| epsilon | double | Το επιτρεπόμενο σφάλμα. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Προσεγγίζει την παρεχόμενη τιμή σε κλάσμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή. |
| epsilon | double | Το επιτρεπόμενο σφάλμα. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο  Object  είναι ίσο με αυτήν την παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το  Object  για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  true  εάν το καθορισμένο  Object  είναι ίσο με αυτήν την παρουσία· διαφορετικά,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Λαμβάνει τον παρονομαστή.

Τιμή: Ο παρονομαστής.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Λαμβάνει τον αριθμητή.

Τιμή: Ο αριθμητής.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Λαμβάνει την τιμή float.

Τιμή: Η τιμή float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Λαμβάνει τη διπλή τιμή.

Τιμή: Η διπλή τιμή.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
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

