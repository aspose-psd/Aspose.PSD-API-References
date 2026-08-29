---
title: "Blend"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει ένα μοτίβο ανάμειξης."
type: docs
weight: 11
url: /el/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Ορίζει ένα μοτίβο ανάμειξης. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

Η τυπική χρήση της κλάσης Blend είναι ο ορισμός ενός μοτίβου ανάμειξης για το πινέλο. Συνεπώς, οι ιδιότητες της ανάμειξης πρέπει να αρχικοποιούνται προσεκτικά. Δεν επιτρέπονται πίνακες null. Το πινέλο θα ρίξει την κατάλληλη εξαίρεση εάν οι πίνακες παραγόντων ή θέσεων της ανάμειξης είναι κενά ή το μήκος τους δεν είναι ίδιο. Εάν υπάρχουν δύο ή περισσότερα στοιχεία στον πίνακα θέσεων, τότε το πρώτο στοιχείο πρέπει να είναι 0 και το τελευταίο 1.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Blend()](#Blend--) | Δημιουργεί ένα νέο αντικείμενο της κλάσης Blend. |
| [Blend(int count)](#Blend-int-) | Δημιουργεί ένα νέο αντικείμενο της κλάσης Blend με τον καθορισμένο αριθμό παραγόντων και θέσεων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει εάν το καθορισμένο αντικείμενο είναι κλάσης com.aspose.psd.Blend και είναι ισοδύναμο με αυτήν την κλάση com.aspose.psd.Blend. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Λαμβάνει τον πίνακα των παραγόντων ανάμειξης για τη διαβάθμιση. |
| [getPositions()](#getPositions--) | Λαμβάνει τον πίνακα των θέσεων ανάμειξης για τη διαβάθμιση. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Ορίζει τον πίνακα των παραγόντων ανάμειξης για τη διαβάθμιση. |
| [setPositions(float[] value)](#setPositions-float---) | Ορίζει τον πίνακα των θέσεων ανάμειξης για τη διαβάθμιση. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης Blend. Ο αριθμός των στοιχείων στους πίνακες παραγόντων και ανάμειξης θα είναι ίσος με 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης Blend με τον καθορισμένο αριθμό παραγόντων και θέσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| count | int | Ο αριθμός των στοιχείων στους πίνακες παραγόντων και θέσεων. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγχει εάν το καθορισμένο αντικείμενο είναι κλάσης com.aspose.psd.Blend και είναι ισοδύναμο με αυτήν την κλάση com.aspose.psd.Blend.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για δοκιμή. |

**Returns:**
boolean - True εάν το obj είναι κλάσης com.aspose.psd.Blend ισοδύναμο με αυτήν την κλάση com.aspose.psd.Blend ; διαφορετικά, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Λαμβάνει τον πίνακα των παραγόντων ανάμειξης για τη διαβάθμιση.

**Returns:**
float[] - Ο πίνακας των παραγόντων ανάμειξης που καθορίζει τα ποσοστά του αρχικού χρώματος και του τελικού χρώματος που θα χρησιμοποιηθούν στη αντίστοιχη θέση.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Λαμβάνει τον πίνακα των θέσεων ανάμειξης για τη διαβάθμιση.

**Returns:**
float[] - Ο πίνακας των θέσεων ανάμειξης που καθορίζει τα ποσοστά της απόστασης κατά μήκος της γραμμής διαβάθμισης.
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




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Ορίζει τον πίνακα των παραγόντων ανάμειξης για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float[] | Ο πίνακας των παραγόντων ανάμειξης που καθορίζει τα ποσοστά του αρχικού χρώματος και του τελικού χρώματος που θα χρησιμοποιηθούν στη αντίστοιχη θέση. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Ορίζει τον πίνακα των θέσεων ανάμειξης για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float[] | Ο πίνακας των θέσεων ανάμειξης που καθορίζει τα ποσοστά της απόστασης κατά μήκος της γραμμής διαβάθμισης. |

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

