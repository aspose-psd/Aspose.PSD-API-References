---
title: "Point"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει ένα ταξινομημένο ζεύγος ακέραιων συντεταγμένων x και y που ορίζει ένα σημείο σε δισδιάστατο επίπεδο."
type: docs
weight: 82
url: /el/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Αντιπροσωπεύει ένα ταξινομημένο ζεύγος ακέραιων συντεταγμένων x και y που ορίζει ένα σημείο σε δισδιάστατο επίπεδο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Aspose.Imaging.Point  με τις καθορισμένες συντεταγμένες. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Aspose.Imaging.Point  από τη δομή  Aspose.Imaging.Size . |
| [Point(int dw)](#Point-int-) | Αρχικοποιεί μια νέα παρουσία της δομής  Aspose.Imaging.Point  χρησιμοποιώντας συντεταγμένες που καθορίζονται από μια ακέραια τιμή. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Αναπαριστά τη μορφή του σημείου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Προσθέτει το καθορισμένο  Aspose.Imaging.Size  στο καθορισμένο  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε  Aspose.Imaging.Point  στρογγυλοποιώντας τις τιμές του  Aspose.Imaging.PointF  προς τις επόμενες υψηλότερες ακέραιες τιμές. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το  Aspose.Imaging.Point  περιέχει τις ίδιες συντεταγμένες με το καθορισμένο  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Αποκτά μια νέα παρουσία της δομής  Aspose.Imaging.Point  που έχει τις τιμές  Aspose.Imaging.Point.X  και  Aspose.Imaging.Point.Y  ορισμένες στο μηδέν. |
| [getX()](#getX--) | Αποκτά ή ορίζει τη συντεταγμένη x αυτού του  Aspose.Imaging.Point . |
| [getY()](#getY--) | Αποκτά ή ορίζει τη συντεταγμένη y αυτού του  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτό το  Aspose.Imaging.Point  είναι κενό. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Μετατοπίζει αυτό το  Aspose.Imaging.Point  κατά το καθορισμένο  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Μετατοπίζει αυτό το  Aspose.Imaging.Point  κατά το καθορισμένο ποσό. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Μετατοπίζει ένα  Aspose.Imaging.Point  κατά ένα δεδομένο  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Συγκρίνει δύο αντικείμενα  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Συγκρίνει δύο αντικείμενα  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Μετατοπίζει ένα  Aspose.Imaging.Point  κατά το αρνητικό ενός δεδομένου  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε αντικείμενο  Aspose.Imaging.Point  στρογγυλοποιώντας τις τιμές του  Aspose.Imaging.Point  προς τον πλησιέστερο ακέραιο. |
| [setX(int value)](#setX-int-) | Αποκτά ή ορίζει τη συντεταγμένη x αυτού του  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Αποκτά ή ορίζει τη συντεταγμένη y αυτού του  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Επιστρέφει το αποτέλεσμα της αφαίρεσης του καθορισμένου  Aspose.Imaging.Size  από το καθορισμένο  Aspose.Imaging.Point . |
| [toString()](#toString--) | Μετατρέπει αυτό το  Aspose.Imaging.Point  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Μετατρέπει τη καθορισμένη δομή  Point  στη δομή  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Μετατρέπει τη καθορισμένη δομή  Aspose.Imaging.Point  σε δομή  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε  Aspose.Imaging.Point  περικόπτοντας τις τιμές του  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Aspose.Imaging.Point  με τις καθορισμένες συντεταγμένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η οριζόντια θέση του σημείου. |
| y | int | Η κάθετη θέση του σημείου. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Aspose.Imaging.Point  από τη δομή  Aspose.Imaging.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Περιέχει τις νέες συντεταγμένες του σημείου. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Αρχικοποιεί μια νέα παρουσία της δομής  Aspose.Imaging.Point  χρησιμοποιώντας συντεταγμένες που καθορίζονται από μια ακέραια τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dw | int | Ένας ακέραιος 32-bit που καθορίζει τις συντεταγμένες για το νέο σημείο. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Αναπαριστά τη μορφή του σημείου.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Προσθέτει το καθορισμένο  Aspose.Imaging.Size  στο καθορισμένο  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  στο οποίο θα προστεθεί. |
| size | [Size](../../com.aspose.psd/size) | Το  Aspose.Imaging.Size  για προσθήκη στο  σημείο . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε  Aspose.Imaging.Point  στρογγυλοποιώντας τις τιμές του  Aspose.Imaging.PointF  προς τις επόμενες υψηλότερες ακέραιες τιμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το  Aspose.Imaging.PointF  για μετατροπή. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το  Aspose.Imaging.Point  περιέχει τις ίδιες συντεταγμένες με το καθορισμένο  System.Object .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το System.Object για δοκιμή. |

**Returns:**
boolean - Αληθές εάν  obj  είναι ένα  Aspose.Imaging.Point  και έχει τις ίδιες συντεταγμένες με αυτό το  Aspose.Imaging.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Αποκτά μια νέα παρουσία της δομής  Aspose.Imaging.Point  που έχει τις τιμές  Aspose.Imaging.Point.X  και  Aspose.Imaging.Point.Y  ορισμένες στο μηδέν.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Αποκτά ή ορίζει τη συντεταγμένη x αυτού του  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Αποκτά ή ορίζει τη συντεταγμένη y αυτού του  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το  Aspose.Imaging.Point .

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτό το  Aspose.Imaging.Point  είναι κενό.

**Returns:**
boolean - Αληθές εάν και τα δύο  Aspose.Imaging.Point.X  και  Aspose.Imaging.Point.Y  είναι 0· διαφορετικά, ψευδές.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Μετατοπίζει αυτό το  Aspose.Imaging.Point  κατά το καθορισμένο  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  που χρησιμοποιείται για μετατόπιση αυτού του  Aspose.Imaging.Point . |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Μετατοπίζει αυτό το  Aspose.Imaging.Point  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | int | Το ποσό για μετατόπιση της συντεταγμένης x. |
| dy | int | Το ποσό για μετατόπιση της συντεταγμένης y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Μετατοπίζει ένα  Aspose.Imaging.Point  κατά ένα δεδομένο  Aspose.Imaging.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  για μετάφραση. |
| size | [Size](../../com.aspose.psd/size) | Ένα  Aspose.Imaging.Size  που καθορίζει το ζεύγος αριθμών για προσθήκη στις συντεταγμένες του  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Συγκρίνει δύο  Aspose.Imaging.Point  αντικείμενα. Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων  Aspose.Imaging.Point.X  και  Aspose.Imaging.Point.Y  των δύο  Aspose.Imaging.Point  αντικειμένων είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Ένα πρώτο  Aspose.Imaging.Point  για σύγκριση. |
| point2 | [Point](../../com.aspose.psd/point) | Ένα δεύτερο  Aspose.Imaging.Point  για σύγκριση. |

**Returns:**
boolean - Αληθές εάν οι τιμές  Aspose.Imaging.Point.X  και  Aspose.Imaging.Point.Y  του  point1  και  point2  είναι ίσες· διαφορετικά, ψευδές.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Συγκρίνει δύο  Aspose.Imaging.Point  αντικείμενα. Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων  Aspose.Imaging.Point.X  ή  Aspose.Imaging.Point.Y  των δύο  Aspose.Imaging.Point  αντικειμένων είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Ένα πρώτο  Aspose.Imaging.Point  για σύγκριση. |
| point2 | [Point](../../com.aspose.psd/point) | Ένα δεύτερο  Aspose.Imaging.Point  για σύγκριση. |

**Returns:**
boolean - Αληθές εάν οι τιμές είτε των ιδιοτήτων  Aspose.Imaging.Point.X  είτε των ιδιοτήτων  Aspose.Imaging.Point.Y  του  point1  και  point2  διαφέρουν· διαφορετικά, ψευδές.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Μετατοπίζει ένα  Aspose.Imaging.Point  κατά το αρνητικό ενός δεδομένου  Aspose.Imaging.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  για μετάφραση. |
| size | [Size](../../com.aspose.psd/size) | Ένα  Aspose.Imaging.Size  που καθορίζει το ζεύγος αριθμών για αφαίρεση από τις συντεταγμένες του  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε αντικείμενο  Aspose.Imaging.Point  στρογγυλοποιώντας τις τιμές του  Aspose.Imaging.Point  προς τον πλησιέστερο ακέραιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το  Aspose.Imaging.PointF  για μετατροπή. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Αποκτά ή ορίζει τη συντεταγμένη x αυτού του  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Αποκτά ή ορίζει τη συντεταγμένη y αυτού του  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Επιστρέφει το αποτέλεσμα της αφαίρεσης του καθορισμένου  Aspose.Imaging.Size  από το καθορισμένο  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  από το οποίο θα αφαιρεθεί. |
| size | [Size](../../com.aspose.psd/size) | Το  Aspose.Imaging.Size  για αφαίρεση από το  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει αυτό το  Aspose.Imaging.Point  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Μετατρέπει τη καθορισμένη δομή  Point  στη δομή  PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Point  για μετατροπή. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Μετατρέπει τη καθορισμένη δομή  Aspose.Imaging.Point  σε δομή  Aspose.Imaging.Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  Aspose.Imaging.Point  για μετατροπή. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Μετατρέπει το καθορισμένο  Aspose.Imaging.PointF  σε  Aspose.Imaging.Point  περικόπτοντας τις τιμές του  Aspose.Imaging.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το  Aspose.Imaging.PointF  για μετατροπή. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

