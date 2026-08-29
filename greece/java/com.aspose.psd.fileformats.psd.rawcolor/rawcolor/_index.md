---
title: "RawColor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η κλάση Raw Color βοηθά στην αποθήκευση χρωμάτων με οποιονδήποτε αριθμό καναλιών, οποιαδήποτε λειτουργία χρώματος και οποιοδήποτε βάθος bit. Παρακαλώ σημειώστε ότι ορισμένες εσωτερικές κλάσεις μπορεί να έχουν προβλήματα με τη μετατροπή του RawColor στη φυσική της μορφή, έτσι εάν το API παρέχει χρώμα CMYK, είναι πιο αξιόπιστο να χρησιμοποιήσετε τη δοθείσα μορφή."
type: docs
weight: 11
url: /el/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Η κλάση Raw Color βοηθά στην αποθήκευση χρωμάτων με οποιονδήποτε αριθμό καναλιών, οποιαδήποτε λειτουργία χρώματος και οποιοδήποτε βάθος bit. Παρακαλώ σημειώστε ότι ορισμένες εσωτερικές κλάσεις μπορεί να έχουν προβλήματα με τη μετατροπή του RawColor στη φυσική της μορφή, έτσι εάν το API παρέχει χρώμα CMYK, είναι πιο αξιόπιστο να χρησιμοποιήσετε τη δοθείσα μορφή. Επίσης, μπορεί να υπάρξουν περιπτώσεις όπου το Raw Color μπορεί να μετατραπεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) από μορφή δεδομένων pixel χρησιμοποιώντας προκαθορισμένες λειτουργίες χρώματος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| [getAsInt()](#getAsInt--) | Λαμβάνει το χρώμα ως int εφόσον είναι δυνατόν να ληφθεί. |
| [getAsLong()](#getAsLong--) | Λαμβάνει το χρώμα ως long εφόσον είναι δυνατόν να ληφθεί. |
| [getBitDepth()](#getBitDepth--) | Λαμβάνει το βάθος bit του Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Λειτουργία που ακολουθεί το χρώμα. |
| [getColorModeName()](#getColorModeName--) | Λαμβάνει το όνομα της λειτουργίας χρώματος. |
| [getComponents()](#getComponents--) | Λαμβάνει τα συστατικά του χρώματος. |
| [hashCode()](#hashCode--) | Λάβετε τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Υλοποιεί τον τελεστή ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Υλοποιεί τον τελεστή !=. |
| [setAsInt(int value)](#setAsInt-int-) | Ορίζει δεδομένα σε όλα τα κανάλια από το όρισμα int εφόσον είναι δυνατόν. |
| [setAsLong(long value)](#setAsLong-long-) | Ορίζει δεδομένα σε όλα τα κανάλια από το όρισμα int εφόσον είναι δυνατόν. |
| [setColorMode(short value)](#setColorMode-short-) | Λειτουργία που ακολουθεί το χρώμα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Τα προσαρμοσμένα συστατικά χρώματος. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) από μορφή δεδομένων pixel χρησιμοποιώντας προκαθορισμένες λειτουργίες χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Η μορφή δεδομένων pixel. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  true  εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία; διαφορετικά,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Λαμβάνει το χρώμα ως int εφόσον είναι δυνατόν να ληφθεί.

**Returns:**
int - Δεδομένα καναλιών αποθηκευμένα σε Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Λαμβάνει το χρώμα ως long εφόσον είναι δυνατόν να ληφθεί.

**Returns:**
long - Δεδομένα καναλιών αποθηκευμένα σε Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Λαμβάνει το βάθος bit του Raw Color. Για παράδειγμα, για χρώμα ARGB με 8 bit ανά κανάλι/συστατικό είναι 32 Bit Depth, του πλήρους χρώματος ARGB με 16 bit ανά κανάλι/συστατικό είναι 64. Το βάθος bit συσσωρεύεται από το άθροισμα των βάθων bit των καναλιών. Είναι δυνατόν εάν διαφορετικά κανάλια έχουν διαφορετικά βάθη bit.

**Returns:**
int - Το άθροισμα όλων των βάθων bit των καναλιών
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Λειτουργία που ακολουθεί το χρώμα.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Λαμβάνει το όνομα της λειτουργίας χρώματος. Το όνομα λειτουργίας χρώματος συσσωρεύεται από τα ονόματα των καναλιών/συστατικών

**Returns:**
java.lang.String - Συμβολοσειρά με το όνομα της λειτουργίας χρώματος
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Λαμβάνει τα συστατικά του χρώματος. Κάθε συστατικό είναι ξεχωριστός κανάλι, και εάν χρησιμοποιείτε μη δημοφιλές σχήμα χρώματος, είναι καλύτερο να εργάζεστε με κάθε κανάλι ξεχωριστά

Τιμή: Τα συστατικά του χρώματος

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λάβετε τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου.

**Returns:**
int - Ο κωδικός κατακερματισμού.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Υλοποιεί τον τελεστή ==.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Το πρώτο RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Το δεύτερο RawColor. |

**Returns:**
boolean - Το αποτέλεσμα του τελεστή.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Υλοποιεί τον τελεστή !=.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Το πρώτο RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Το δεύτερο RawColor. |

**Returns:**
boolean - Το αποτέλεσμα του τελεστή.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Ορίζει δεδομένα σε όλα τα κανάλια από το όρισμα int εφόσον είναι δυνατόν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η τιμή int που περιέχει τα δεδομένα του συστατικού |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Ορίζει δεδομένα σε όλα τα κανάλια από το όρισμα int εφόσον είναι δυνατόν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Η τιμή int που περιέχει τα δεδομένα του συστατικού |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Λειτουργία που ακολουθεί το χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

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

