---
title: "Cache"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιέχει ρυθμίσεις κρυφής μνήμης."
type: docs
weight: 14
url: /el/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Περιέχει ρυθμίσεις κρυφής μνήμης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Λαμβάνει τον αριθμό των εκχωρημένων byte δίσκου. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Λαμβάνει τον αριθμό των εκχωρημένων byte στη μνήμη. |
| [getCacheFolder()](#getCacheFolder--) | Λαμβάνει το φάκελο της κρυφής μνήμης. |
| [getCacheType()](#getCacheType--) | Λαμβάνει ή ορίζει το χρησιμοποιούμενο σχήμα κρυφής μνήμης. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η επανεκχώρηση πρέπει να είναι ακριβής ή όχι. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Λαμβάνει το μέγιστο διαθέσιμο χώρο δίσκου για την κρυφή μνήμη. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Λαμβάνει τη μέγιστη διαθέσιμη μνήμη για την κρυφή μνήμη στη μνήμη. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Ορίζει το φάκελο της κρυφής μνήμης. |
| [setCacheType(int value)](#setCacheType-int-) | Ορίζει το χρησιμοποιούμενο σχήμα κρυφής μνήμης. |
| [setDefaults()](#setDefaults--) | Ορίζει τις ρυθμίσεις της  Cache  στις προεπιλογές. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η επανεκχώρηση πρέπει να είναι ακριβής ή όχι. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Ορίζει το μέγιστο διαθέσιμο χώρο δίσκου για την κρυφή μνήμη. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Ορίζει τη μέγιστη διαθέσιμη μνήμη για την κρυφή μνήμη στη μνήμη. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Λαμβάνει τον αριθμό των εκχωρημένων byte δίσκου.

**Returns:**
long - Ο εκχωρημένος αριθμός byte δίσκου.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Λαμβάνει τον αριθμό των εκχωρημένων byte στη μνήμη.

**Returns:**
long - Ο εκχωρημένος αριθμός byte στη μνήμη.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Λαμβάνει το φάκελο της κρυφής μνήμης.

**Returns:**
java.lang.String - Ο φάκελος της κρυφής μνήμης.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Λαμβάνει ή ορίζει το χρησιμοποιούμενο σχήμα κρυφής μνήμης.

**Returns:**
int - Το χρησιμοποιούμενο σχήμα κρυφής μνήμης.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η επανεκχώρηση πρέπει να είναι ακριβής ή όχι. Εάν η επανεκχώρηση δεν είναι ακριβής, η απόδοση θα πρέπει να είναι υψηλότερη.

**Returns:**
boolean -  true  εάν η επανεκχώρηση είναι ακριβής· διαφορετικά,  false .

Η ακριβής επανεκχώρηση θα εκτελεί επανεκχώρηση πρόσθετης μνήμης μόνο μέχρι το καθορισμένο άνω όριο. Κατά τη μεταβίβαση του άνω ορίου για τη μνήμη εντός μνήμης κατά τη διάρκεια της επανεκχώρησης, τα δεδομένα στην κρυφή μνήμη θα αντιγραφούν στον δίσκο εάν είναι δυνατόν. Κατά τη μεταβίβαση του άνω ορίου για τη μνήμη δίσκου κατά τη διάρκεια της επανεκχώρησης, θα ριχτεί η κατάλληλη εξαίρεση. Η απόδοση θα πρέπει να είναι υψηλότερη εάν αυτή η επιλογή απενεργοποιηθεί, καθώς δεν θα γίνει πρόσθετη αντιγραφή εάν είναι δυνατόν, ωστόσο αυτό μπορεί επίσης να οδηγήσει στην παράκαμψη των καθορισμένων άνω ορίων για μνήμη ή δίσκο.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Λαμβάνει το μέγιστο διαθέσιμο χώρο δίσκου για την κρυφή μνήμη. Η καθορισμένη τιμή είναι ο αριθμός των megabytes.

**Returns:**
int - Η μέγιστη διαθέσιμη χωρητικότητα δίσκου για την προσωρινή μνήμη.

Η τιμή 0 θα καταναλώσει όλη τη διαθέσιμη μνήμη και λειτουργεί ως χωρίς άνω όριο.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Αποκτά τη μέγιστη διαθέσιμη μνήμη για την προσωρινή μνήμη στη μνήμη. Η καθορισμένη τιμή είναι ο αριθμός των megabytes.

**Returns:**
int - Η μέγιστη μνήμη για την προσωρινή μνήμη.

Η τιμή 0 θα καταναλώσει όλη τη διαθέσιμη μνήμη και λειτουργεί ως χωρίς άνω όριο.
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




### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Ορίζει το φάκελο της κρυφής μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Ο φάκελος προσωρινής μνήμης. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Ορίζει το χρησιμοποιούμενο σχήμα κρυφής μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το χρησιμοποιούμενο σχήμα προσωρινής μνήμης. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Ορίζει τις ρυθμίσεις της  Cache  στις προεπιλογές.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν η επανακατανομή πρέπει να είναι ακριβής ή όχι. Εάν η επανακατανομή δεν είναι ακριβής, η απόδοση θα πρέπει να είναι υψηλότερη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true εάν η επανακατανομή είναι ακριβής· διαφορετικά, false. |

Η ακριβής επανακατανομή θα εκτελεί επανακατανομή πρόσθετης μνήμης μόνο μέχρι το καθορισμένο άνω όριο. Κατά τη μεταβίβαση άνω ορίου για τη μνήμη εντός μνήμης κατά την επανακατανομή, τα προσωρινά δεδομένα θα αντιγραφούν στον δίσκο εάν είναι δυνατόν. Κατά τη μεταβίβαση άνω ορίου για τη μνήμη δίσκου κατά την επανακατανομή, θα ριχτεί η κατάλληλη εξαίρεση. Η απόδοση θα πρέπει να είναι υψηλότερη εάν αυτή η επιλογή απενεργοποιηθεί, καθώς δεν θα γίνει επιπλέον αντιγραφή εάν είναι δυνατόν, ωστόσο αυτό μπορεί επίσης να οδηγήσει σε υπέρβαση των καθορισμένων ανώτερων ορίων για μνήμη ή δίσκο. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Ορίζει τη μέγιστη διαθέσιμη χωρητικότητα δίσκου για την προσωρινή μνήμη. Η καθορισμένη τιμή είναι ο αριθμός των megabytes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η μέγιστη διαθέσιμη χωρητικότητα δίσκου για την προσωρινή μνήμη. |

Η τιμή 0 θα καταναλώσει όλη τη διαθέσιμη μνήμη και λειτουργεί ως χωρίς άνω όριο. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Ορίζει τη μέγιστη διαθέσιμη μνήμη για την προσωρινή μνήμη στη μνήμη. Η καθορισμένη τιμή είναι ο αριθμός των megabytes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η μέγιστη μνήμη για την προσωρινή μνήμη. |

Η τιμή 0 θα καταναλώσει όλη τη διαθέσιμη μνήμη και λειτουργεί ως χωρίς άνω όριο. |

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

