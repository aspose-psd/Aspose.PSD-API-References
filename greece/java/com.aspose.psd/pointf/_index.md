---
title: "PointF"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει ένα ταξινομημένο ζεύγος δεκαδικών συντεταγμένων x και y που ορίζει ένα σημείο σε δισδιάστατο επίπεδο."
type: docs
weight: 83
url: /el/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Αντιπροσωπεύει ένα ταξινομημένο ζεύγος δεκαδικών συντεταγμένων x και y που ορίζει ένα σημείο σε δισδιάστατο επίπεδο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Αρχικοποιεί ένα νέο παράδειγμα της  com.aspose.psd.PointF  δομής με τις καθορισμένες συντεταγμένες. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | Μετατοπίζει ένα δεδομένο  com.aspose.psd.PointF  με το καθορισμένο  com.aspose.psd.Size . |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Μετατοπίζει ένα δεδομένο  com.aspose.psd.PointF  με ένα καθορισμένο  com.aspose.psd.SizeF . |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το  com.aspose.psd.PointF  περιέχει τις ίδιες συντεταγμένες με το καθορισμένο  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Λαμβάνει ένα νέο παράδειγμα της  com.aspose.psd.PointF  δομής που έχει τις τιμές  com.aspose.psd.PointF.X  και  com.aspose.psd.PointF.Y  ορισμένες στο μηδέν. |
| [getX()](#getX--) | Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού του  com.aspose.psd.PointF . |
| [getY()](#getY--) | Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού του  com.aspose.psd.PointF . |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό hash για αυτήν τη  com.aspose.psd.PointF  δομή. |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  com.aspose.psd.PointF  είναι κενό. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | Μετατοπίζει ένα  com.aspose.psd.PointF  με ένα δεδομένο  com.aspose.psd.Size . |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Μετατοπίζει το  com.aspose.psd.PointF  με το καθορισμένο  com.aspose.psd.SizeF . |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Συγκρίνει δύο δομές  com.aspose.psd.PointF . |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Καθορίζει εάν οι συντεταγμένες των καθορισμένων σημείων δεν είναι ίσες. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός δεδομένου com.aspose.psd.Size . |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου com.aspose.psd.SizeF . |
| [setX(float value)](#setX-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού του  com.aspose.psd.PointF . |
| [setY(float value)](#setY-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού του  com.aspose.psd.PointF . |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου μεγέθους. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου μεγέθους. |
| [toString()](#toString--) | Μετατρέπει αυτό το com.aspose.psd.PointF σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Αρχικοποιεί ένα νέο παράδειγμα της  com.aspose.psd.PointF  δομής με τις καθορισμένες συντεταγμένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η οριζόντια θέση του σημείου. |
| y | float | Η κάθετη θέση του σημείου. |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


Μετατοπίζει ένα δεδομένο  com.aspose.psd.PointF  με το καθορισμένο  com.aspose.psd.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [Size](../../com.aspose.psd/size) | Το com.aspose.psd.Size που καθορίζει τους αριθμούς που θα προστεθούν στις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Μετατοπίζει ένα δεδομένο  com.aspose.psd.PointF  με ένα καθορισμένο  com.aspose.psd.SizeF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [SizeF](../../com.aspose.psd/sizef) | Το com.aspose.psd.SizeF που καθορίζει τους αριθμούς που θα προστεθούν στις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το  com.aspose.psd.PointF  περιέχει τις ίδιες συντεταγμένες με το καθορισμένο  System.Object .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το System.Object για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το obj είναι ένα com.aspose.psd.PointF και έχει τις ίδιες συντεταγμένες με αυτό το com.aspose.psd.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Λαμβάνει ένα νέο παράδειγμα της  com.aspose.psd.PointF  δομής που έχει τις τιμές  com.aspose.psd.PointF.X  και  com.aspose.psd.PointF.Y  ορισμένες στο μηδέν.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού του  com.aspose.psd.PointF .

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού του  com.aspose.psd.PointF .

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό hash για αυτήν τη  com.aspose.psd.PointF  δομή.

**Returns:**
int - Μια ακέραια τιμή που καθορίζει μια τιμή κατακερματισμού για αυτή τη δομή com.aspose.psd.PointF .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  com.aspose.psd.PointF  είναι κενό.

**Returns:**
boolean - True εάν και τα δύο com.aspose.psd.PointF.X και com.aspose.psd.PointF.Y είναι 0· διαφορετικά, false.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Μετατοπίζει ένα  com.aspose.psd.PointF  με ένα δεδομένο  com.aspose.psd.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [Size](../../com.aspose.psd/size) | Ένα com.aspose.psd.Size που καθορίζει το ζεύγος αριθμών που θα προστεθούν στις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Μετατοπίζει το  com.aspose.psd.PointF  με το καθορισμένο  com.aspose.psd.SizeF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [SizeF](../../com.aspose.psd/sizef) | Το com.aspose.psd.SizeF που καθορίζει τους αριθμούς που θα προστεθούν στις x- και y-συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Συγκρίνει δύο com.aspose.psd.PointF δομές. Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων com.aspose.psd.PointF.X και com.aspose.psd.PointF.Y των δύο com.aspose.psd.PointF δομών είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Ένα πρώτο com.aspose.psd.PointF για σύγκριση. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Ένα δεύτερο com.aspose.psd.PointF για σύγκριση. |

**Returns:**
boolean - True εάν οι τιμές com.aspose.psd.PointF.X και com.aspose.psd.PointF.Y των πρώτων και δεύτερων com.aspose.psd.PointF δομών είναι ίσες· διαφορετικά, false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Καθορίζει εάν οι συντεταγμένες των καθορισμένων σημείων δεν είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Ένα πρώτο com.aspose.psd.PointF για σύγκριση. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Ένα δεύτερο com.aspose.psd.PointF για σύγκριση. |

**Returns:**
boolean - True για να υποδείξει ότι οι τιμές com.aspose.psd.PointF.X και com.aspose.psd.PointF.Y των point1 και point2 δεν είναι ίσες· διαφορετικά, false.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός δεδομένου com.aspose.psd.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ένα com.aspose.psd.PointF για μετακίνηση. |
| size | [Size](../../com.aspose.psd/size) | Ένα com.aspose.psd.Size που καθορίζει τους αριθμούς που θα αφαιρεθούν από τις x- και y-συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου com.aspose.psd.SizeF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [SizeF](../../com.aspose.psd/sizef) | Το com.aspose.psd.SizeF που καθορίζει τους αριθμούς που θα αφαιρεθούν από τις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού του  com.aspose.psd.PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού του  com.aspose.psd.PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου μεγέθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [Size](../../com.aspose.psd/size) | Το com.aspose.psd.Size που καθορίζει τους αριθμούς που θα αφαιρεθούν από τις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Μετακινεί ένα com.aspose.psd.PointF με το αντίθετο ενός καθορισμένου μεγέθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για μετακίνηση. |
| size | [SizeF](../../com.aspose.psd/sizef) | Το com.aspose.psd.SizeF που καθορίζει τους αριθμούς που θα αφαιρεθούν από τις συντεταγμένες του point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει αυτό το com.aspose.psd.PointF σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το com.aspose.psd.PointF .
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

