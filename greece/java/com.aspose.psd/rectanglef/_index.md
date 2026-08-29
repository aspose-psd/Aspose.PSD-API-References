---
title: "RectangleF"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αποθηκεύει ένα σύνολο τεσσάρων δεκαδικών αριθμών που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου."
type: docs
weight: 89
url: /el/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Αποθηκεύει ένα σύνολο τεσσάρων δεκαδικών αριθμών που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  με την καθορισμένη θέση και μέγεθος. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  με την καθορισμένη θέση και μέγεθος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF . |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Καθορίζει αν η ορθογώνια περιοχή που αντιπροσωπεύεται από το  rect  περιέχεται πλήρως μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF . |
| [contains(float x, float y)](#contains-float-float-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF . |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Διαιρεί τις τρέχουσες τιμές του ορθογωνίου για να μετασχηματίσει τις κάθετες και οριζόντιες τιμές κλίμακας του πίνακα και επιστρέφει ένα νέο [RectangleF](../../com.aspose.psd/rectanglef) αντικείμενο με τις τιμές αποτελέσματος. |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει αν το  obj  είναι ένα  com.aspose.psd.RectangleF  με την ίδια θέση και μέγεθος αυτής της  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Δημιουργεί μια δομή  com.aspose.psd.RectangleF  με την πάνω αριστερή γωνία και την κάτω δεξιά γωνία στις καθορισμένες θέσεις. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Δημιουργεί ένα νέο  Rectangle  από δύο καθορισμένα σημεία. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.RectangleF.Y  και του  com.aspose.psd.RectangleF.Height  αυτής της δομής  com.aspose.psd.RectangleF . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Λαμβάνει μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  που έχει τις τιμές  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  και  com.aspose.psd.RectangleF.Height  μηδενισμένες. |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.RectangleF . |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής  com.aspose.psd.RectangleF . |
| [getLocation()](#getLocation--) | Λαμβάνει ή ορίζει τις συντεταγμένες της πάνω αριστερής γωνίας αυτής της δομής  com.aspose.psd.RectangleF . |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.RectangleF.X  και του  com.aspose.psd.RectangleF.Width  αυτού του  com.aspose.psd.RectangleF  δομής. |
| [getSize()](#getSize--) | Λαμβάνει ή ορίζει το μέγεθος αυτού του  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτού του  com.aspose.psd.RectangleF  δομής. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος αυτού του  com.aspose.psd.RectangleF  δομής. |
| [getX()](#getX--) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής. |
| [getY()](#getY--) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής. |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού για αυτήν τη  com.aspose.psd.RectangleF  δομή. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Δημιουργεί και επιστρέφει ένα φουσκωμένο αντίγραφο της καθορισμένης  com.aspose.psd.RectangleF  δομής. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Φουσκώνει αυτό το  com.aspose.psd.RectangleF  κατά το καθορισμένο ποσό. |
| [inflate(float x, float y)](#inflate-float-float-) | Φουσκώνει αυτή τη  com.aspose.psd.RectangleF  δομή κατά το καθορισμένο ποσό. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Αντικαθιστά αυτή τη  com.aspose.psd.RectangleF  δομή με τη διατομή της με την καθορισμένη  com.aspose.psd.RectangleF  δομή. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Επιστρέφει μια  com.aspose.psd.RectangleF  δομή που αντιπροσωπεύει τη διατομή δύο ορθογωνίων. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Καθορίζει εάν αυτό το ορθογώνιο τέμνει το  rect . |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ιδιότητα  com.aspose.psd.RectangleF.Width  ή  com.aspose.psd.RectangleF.Height  αυτού του  com.aspose.psd.RectangleF  έχει τιμή μηδέν. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Πολλαπλασιάζει τις τρέχουσες τιμές του ορθογωνίου για να μετασχηματίσει τις κάθετες και οριζόντιες τιμές κλίμακας του πίνακα και επιστρέφει ένα νέο αντικείμενο [RectangleF](../../com.aspose.psd/rectanglef) με τις τιμές αποτελέσματος. |
| [normalize()](#normalize--) | Κανονικοποιεί το ορθογώνιο καθιστώντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το άνω μικρότερο από το κάτω. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [offset(float x, float y)](#offset-float-float-) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Υλοποιεί τον τελεστή /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Δοκιμάζει εάν δύο  com.aspose.psd.RectangleF  δομές έχουν ίση θέση και μέγεθος. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Δοκιμάζει εάν δύο  com.aspose.psd.RectangleF  δομές διαφέρουν στη θέση ή στο μέγεθος. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Υλοποιεί τον τελεστή \*. |
| [setBottom(float value)](#setBottom-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.RectangleF.Y  και του  com.aspose.psd.RectangleF.Height  αυτής της δομής  com.aspose.psd.RectangleF . |
| [setHeight(float value)](#setHeight-float-) | Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.RectangleF . |
| [setLeft(float value)](#setLeft-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής  com.aspose.psd.RectangleF . |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Λαμβάνει ή ορίζει τις συντεταγμένες της πάνω αριστερής γωνίας αυτής της δομής  com.aspose.psd.RectangleF . |
| [setRight(float value)](#setRight-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.RectangleF.X  και του  com.aspose.psd.RectangleF.Width  αυτού του  com.aspose.psd.RectangleF  δομής. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Λαμβάνει ή ορίζει το μέγεθος αυτού του  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτού του  com.aspose.psd.RectangleF  δομής. |
| [setWidth(float value)](#setWidth-float-) | Λαμβάνει ή ορίζει το πλάτος αυτού του  com.aspose.psd.RectangleF  δομής. |
| [setX(float value)](#setX-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής. |
| [setY(float value)](#setY-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Μετατρέπει ένα [RectangleF](../../com.aspose.psd/rectanglef) σε μια δομή [Rectangle](../../com.aspose.psd/rectangle) με περικομμένες τιμές ορθογωνίου. |
| [toString()](#toString--) | Μετατρέπει τα χαρακτηριστικά αυτού του  com.aspose.psd.RectangleF  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Μετατρέπει τη καθορισμένη  com.aspose.psd.Rectangle  δομή σε μια  com.aspose.psd.RectangleF  δομή. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου. |
| πλάτος | float | Το πλάτος του ορθογωνίου. |
| ύψος | float | Το ύψος του ορθογωνίου. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Ένα com.aspose.psd.PointF που αντιπροσωπεύει την επάνω αριστερή γωνία της ορθογώνιας περιοχής. |
| size | [SizeF](../../com.aspose.psd/sizef) | Ένα com.aspose.psd.SizeF που αντιπροσωπεύει το πλάτος και το ύψος της ορθογώνιας περιοχής. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Το com.aspose.psd.PointF για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το σημείο που αντιπροσωπεύεται από την παράμετρο point περιέχεται μέσα σε αυτή τη δομή com.aspose.psd.RectangleF· διαφορετικά false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Καθορίζει αν η ορθογώνια περιοχή που αντιπροσωπεύεται από το  rect  περιέχεται πλήρως μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Το com.aspose.psd.RectangleF για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το rect περιέχεται πλήρως μέσα στην ορθογώνια περιοχή που αντιπροσωπεύεται από αυτό το com.aspose.psd.RectangleF· διαφορετικά false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το σημείο που ορίζεται από τα x και y περιέχεται μέσα σε αυτή τη δομή com.aspose.psd.RectangleF· διαφορετικά false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Διαιρεί τις τρέχουσες τιμές του ορθογωνίου για να μετασχηματίσει τις κάθετες και οριζόντιες τιμές κλίμακας του πίνακα και επιστρέφει ένα νέο [RectangleF](../../com.aspose.psd/rectanglef) αντικείμενο με τις τιμές αποτελέσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transformMatrix | double[] | Ο πίνακας μετασχηματισμού του στρώματος. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δοκιμάζει αν το  obj  είναι ένα  com.aspose.psd.RectangleF  με την ίδια θέση και μέγεθος αυτής της  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το System.Object για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν obj είναι ένα com.aspose.psd.RectangleF και οι ιδιότητες X, Y, Width και Height του είναι ίσες με τις αντίστοιχες ιδιότητες αυτού του com.aspose.psd.RectangleF· διαφορετικά false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Δημιουργεί μια δομή  com.aspose.psd.RectangleF  με την πάνω αριστερή γωνία και την κάτω δεξιά γωνία στις καθορισμένες θέσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | float | Η συντεταγμένη x της επάνω αριστερής γωνίας της ορθογώνιας περιοχής. |
| top | float | Η συντεταγμένη y της επάνω αριστερής γωνίας της ορθογώνιας περιοχής. |
| right | float | Η συντεταγμένη x της κάτω δεξιάς γωνίας της ορθογώνιας περιοχής. |
| bottom | float | Η συντεταγμένη y της κάτω δεξιάς γωνίας της ορθογώνιας περιοχής. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Δημιουργεί ένα νέο  Rectangle  από δύο καθορισμένα σημεία. Τα δύο κορυφαία σημεία του δημιουργημένου  Rectangle  θα είναι ίσα με τα περασμένα  point1  και  point2 . Αυτά θα είναι συνήθως τα αντίθετα κορυφαία σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Το πρώτο  Point  για το νέο rectangle. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Το δεύτερο  Point  για το νέο rectangle. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.RectangleF.Y  και του  com.aspose.psd.RectangleF.Height  αυτής της δομής  com.aspose.psd.RectangleF .

**Returns:**
float - Η συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.RectangleF.Y  και του  com.aspose.psd.RectangleF.Height  αυτής της  com.aspose.psd.RectangleF  δομής.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Λαμβάνει μια νέα παρουσία της δομής  com.aspose.psd.RectangleF  που έχει τις τιμές  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  και  com.aspose.psd.RectangleF.Height  μηδενισμένες.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.RectangleF .

**Returns:**
float - Το ύψος αυτής της  com.aspose.psd.RectangleF  δομής.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής  com.aspose.psd.RectangleF .

**Returns:**
float - Η συντεταγμένη x της αριστερής άκρης αυτής της  com.aspose.psd.RectangleF  δομής.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Λαμβάνει ή ορίζει τις συντεταγμένες της πάνω αριστερής γωνίας αυτής της δομής  com.aspose.psd.RectangleF .

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.RectangleF.X  και του  com.aspose.psd.RectangleF.Width  αυτού του  com.aspose.psd.RectangleF  δομής.

**Returns:**
float - Η συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.RectangleF.X  και του  com.aspose.psd.RectangleF.Width  αυτής της  com.aspose.psd.RectangleF  δομής.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Λαμβάνει ή ορίζει το μέγεθος αυτού του  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτού του  com.aspose.psd.RectangleF  δομής.

**Returns:**
float - Η συντεταγμένη y της άνω άκρης αυτής της  com.aspose.psd.RectangleF  δομής.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Λαμβάνει ή ορίζει το πλάτος αυτού του  com.aspose.psd.RectangleF  δομής.

**Returns:**
float - Το πλάτος αυτής της  com.aspose.psd.RectangleF  δομής.
### getX() {#getX--}
```
public float getX()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής.

**Returns:**
float - Η συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της  com.aspose.psd.RectangleF  δομής.
### getY() {#getY--}
```
public float getY()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής.

**Returns:**
float - Η συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της  com.aspose.psd.RectangleF  δομής.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού για αυτήν τη  com.aspose.psd.RectangleF  δομή.

**Returns:**
int - Ο κωδικός κατακερματισμού για αυτή τη  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Δημιουργεί και επιστρέφει ένα φουσκωμένο αντίγραφο της καθορισμένης  com.aspose.psd.RectangleF  δομής. Το αντίγραφο φουσκώνεται κατά το καθορισμένο ποσό. Το αρχικό rectangle παραμένει αμετάβλητο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Το  com.aspose.psd.RectangleF  που θα αντιγραφεί. Αυτό το rectangle δεν τροποποιείται. |
| x | float | Το ποσό για τη φούσκωση του αντιγράφου του rectangle οριζόντια. |
| y | float | Το ποσό για τη φούσκωση του αντιγράφου του rectangle κάθετα. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Φουσκώνει αυτό το  com.aspose.psd.RectangleF  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Το ποσό για τη φούσκωση αυτού του rectangle. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Φουσκώνει αυτή τη  com.aspose.psd.RectangleF  δομή κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Το ποσό για τη φούσκωση αυτής της  com.aspose.psd.RectangleF  δομής οριζόντια. |
| y | float | Το ποσό για τη φούσκωση αυτής της  com.aspose.psd.RectangleF  δομής κάθετα. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Αντικαθιστά αυτή τη  com.aspose.psd.RectangleF  δομή με τη διατομή της με την καθορισμένη  com.aspose.psd.RectangleF  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Το rectangle για τομή. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Επιστρέφει μια  com.aspose.psd.RectangleF  δομή που αντιπροσωπεύει τη διατομή δύο rectangles. Εάν δεν υπάρχει διατομή, επιστρέφεται ένα κενό  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα πρώτο rectangle για διατομή. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα δεύτερο rectangle για διατομή. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Καθορίζει εάν αυτό το ορθογώνιο τέμνει το  rect .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Το rectangle για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν υπάρχει οποιαδήποτε διατομή.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ιδιότητα  com.aspose.psd.RectangleF.Width  ή  com.aspose.psd.RectangleF.Height  αυτού του  com.aspose.psd.RectangleF  έχει τιμή μηδέν.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν η ιδιότητα com.aspose.psd.RectangleF.Width ή com.aspose.psd.RectangleF.Height αυτού του com.aspose.psd.RectangleF έχει τιμή μηδέν· διαφορετικά, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Πολλαπλασιάζει τις τρέχουσες τιμές του ορθογωνίου για να μετασχηματίσει τις κάθετες και οριζόντιες τιμές κλίμακας του πίνακα και επιστρέφει ένα νέο αντικείμενο [RectangleF](../../com.aspose.psd/rectanglef) με τις τιμές αποτελέσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transformMatrix | double[] | Ο πίνακας μετασχηματισμού του στρώματος. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Κανονικοποιεί το ορθογώνιο καθιστώντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το άνω μικρότερο από το κάτω.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Το ποσό για μετατόπιση της θέσης. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Το ποσό για μετατόπιση της θέσης οριζόντια. |
| y | float | Το ποσό για μετατόπιση της θέσης κάθετα. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Υλοποιεί τον τελεστή /.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο. |
| διαχωριστικό | float | Το διαχωριστικό. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Δοκιμάζει εάν δύο  com.aspose.psd.RectangleF  δομές έχουν ίση θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF που βρίσκεται αριστερά του τελεστή ισότητας. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF που βρίσκεται δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οι δύο καθορισμένες δομές com.aspose.psd.RectangleF έχουν ίσες τις ιδιότητες com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width και com.aspose.psd.RectangleF.Height.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Δοκιμάζει εάν δύο  com.aspose.psd.RectangleF  δομές διαφέρουν στη θέση ή στο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF που βρίσκεται αριστερά του τελεστή ανισότητας. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF που βρίσκεται δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οποιαδήποτε από τις ιδιότητες com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width ή com.aspose.psd.RectangleF.Height των δύο δομών com.aspose.psd.RectangleF είναι διαφορετική· διαφορετικά false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Υλοποιεί τον τελεστή \*.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο. |
| πολλαπλασιαστής | float | Ο πολλαπλασιαστής. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.RectangleF.Y  και του  com.aspose.psd.RectangleF.Height  αυτής της δομής  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Λαμβάνει ή ορίζει τις συντεταγμένες της πάνω αριστερής γωνίας αυτής της δομής  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.RectangleF.X  και του  com.aspose.psd.RectangleF.Width  αυτού του  com.aspose.psd.RectangleF  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Λαμβάνει ή ορίζει το μέγεθος αυτού του  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτού του  com.aspose.psd.RectangleF  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Λαμβάνει ή ορίζει το πλάτος αυτού του  com.aspose.psd.RectangleF  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτού του  com.aspose.psd.RectangleF  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Μετατρέπει ένα [RectangleF](../../com.aspose.psd/rectanglef) σε μια δομή [Rectangle](../../com.aspose.psd/rectangle) με περικομμένες τιμές ορθογωνίου.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει τα χαρακτηριστικά αυτού του  com.aspose.psd.RectangleF  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Μια συμβολοσειρά που περιέχει τη θέση, το πλάτος και το ύψος αυτής της δομής com.aspose.psd.RectangleF.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Μετατρέπει τη καθορισμένη  com.aspose.psd.Rectangle  δομή σε μια  com.aspose.psd.RectangleF  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή com.aspose.psd.Rectangle προς μετατροπή. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Το πρώτο ορθογώνιο για ένωση. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Το δεύτερο ορθογώνιο για ένωση. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

