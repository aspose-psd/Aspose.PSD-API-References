---
title: "Rectangle"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου."
type: docs
weight: 88
url: /el/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Αποθηκεύει ένα σύνολο τεσσάρων ακεραίων που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  με την καθορισμένη θέση και μέγεθος. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  με την καθορισμένη θέση και μέγεθος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Μετατρέπει τη συγκεκριμένη δομή  com.aspose.psd.RectangleF  σε δομή  com.aspose.psd.Rectangle  στρογγυλοποιώντας τις τιμές της  com.aspose.psd.RectangleF  προς τις επόμενες μεγαλύτερες ακέραιες τιμές. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle . |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το  rect  περιέχεται πλήρως μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle . |
| [contains(int x, int y)](#contains-int-int-) | Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει εάν το  obj  είναι μια δομή  com.aspose.psd.Rectangle  με την ίδια θέση και μέγεθος με αυτή τη δομή  com.aspose.psd.Rectangle . |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Δημιουργεί μια δομή  com.aspose.psd.Rectangle  με τις καθορισμένες θέσεις των άκρων. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Δημιουργεί ένα νέο  Rectangle  από δύο καθορισμένα σημεία. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.Y  και  com.aspose.psd.Rectangle.Height  αυτής της δομής  com.aspose.psd.Rectangle . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Λαμβάνει μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  που έχει τις τιμές  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  και  com.aspose.psd.Rectangle.Height  ορισμένες στο μηδέν. |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.Rectangle . |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτής της δομής  com.aspose.psd.Rectangle . |
| [getLocation()](#getLocation--) | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.X  και  com.aspose.psd.Rectangle.Width  αυτής της δομής  com.aspose.psd.Rectangle . |
| [getSize()](#getSize--) | Λαμβάνει ή ορίζει το μέγεθος αυτής της  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω άκρου αυτής της δομής  com.aspose.psd.Rectangle . |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτής της δομής  com.aspose.psd.Rectangle . |
| [getX()](#getX--) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [getY()](#getY--) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη δομή  com.aspose.psd.Rectangle . |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Δημιουργεί και επιστρέφει ένα διογκωμένο αντίγραφο της καθορισμένης δομής  com.aspose.psd.Rectangle . |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Διογκώνει αυτή τη δομή  com.aspose.psd.Rectangle  κατά το καθορισμένο ποσό. |
| [inflate(int width, int height)](#inflate-int-int-) | Διογκώνει αυτή τη δομή  com.aspose.psd.Rectangle  κατά το καθορισμένο ποσό. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Αντικαθιστά αυτή τη δομή  com.aspose.psd.Rectangle  με την τομή του εαυτού της και της καθορισμένης δομής  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Επιστρέφει μια τρίτη δομή  com.aspose.psd.Rectangle  που αντιπροσωπεύει την τομή δύο άλλων δομών  com.aspose.psd.Rectangle . |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Καθορίζει εάν αυτό το ορθογώνιο τέμνει το  rect . |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν όλες οι αριθμητικές ιδιότητες αυτής της δομής  com.aspose.psd.Rectangle  έχουν τιμές μηδέν. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η  Rectangle  είναι τουλάχιστον εν μέρει ορατή |
| [normalize()](#normalize--) | Κανονικοποιεί το ορθογώνιο καθιστώντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το άνω μικρότερο από το κάτω. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [offset(int x, int y)](#offset-int-int-) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Δοκιμάζει εάν δύο δομές  com.aspose.psd.Rectangle  έχουν ίση θέση και μέγεθος. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Δοκιμάζει εάν δύο  com.aspose.psd.Rectangle  δομές διαφέρουν σε θέση ή μέγεθος. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Μετατρέπει το καθορισμένο  com.aspose.psd.RectangleF  σε  com.aspose.psd.Rectangle  στρογγυλοποιώντας τις τιμές του  com.aspose.psd.RectangleF  στο πλησιέστερο ακέραιο. |
| [setBottom(int value)](#setBottom-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.Y  και  com.aspose.psd.Rectangle.Height  αυτής της δομής  com.aspose.psd.Rectangle . |
| [setHeight(int value)](#setHeight-int-) | Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.Rectangle . |
| [setLeft(int value)](#setLeft-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτής της δομής  com.aspose.psd.Rectangle . |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [setRight(int value)](#setRight-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.X  και  com.aspose.psd.Rectangle.Width  αυτής της δομής  com.aspose.psd.Rectangle . |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Λαμβάνει ή ορίζει το μέγεθος αυτής της  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω άκρου αυτής της δομής  com.aspose.psd.Rectangle . |
| [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος αυτής της  com.aspose.psd.Rectangle  δομής. |
| [setX(int value)](#setX-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [setY(int value)](#setY-int-) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle . |
| [toString()](#toString--) | Μετατρέπει τα χαρακτηριστικά αυτής της  com.aspose.psd.Rectangle  σε αναγνώσιμη για άνθρωπο συμβολοσειρά. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Μετατρέπει το καθορισμένο  com.aspose.psd.RectangleF  σε  com.aspose.psd.Rectangle  περικόπτοντας τις τιμές του  com.aspose.psd.RectangleF . |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Λαμβάνει μια  com.aspose.psd.Rectangle  δομή που περιέχει την ένωση δύο  com.aspose.psd.Rectangle  δομών. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου. |
| πλάτος | int | Το πλάτος του ορθογωνίου. |
| ύψος | int | Το ύψος του ορθογωνίου. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Αρχικοποιεί μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Ένα  com.aspose.psd.Point  που αντιπροσωπεύει την επάνω αριστερή γωνία της ορθογώνιας περιοχής. |
| size | [Size](../../com.aspose.psd/size) | Ένα  com.aspose.psd.Size  που αντιπροσωπεύει το πλάτος και το ύψος της ορθογώνιας περιοχής. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Μετατρέπει τη συγκεκριμένη δομή  com.aspose.psd.RectangleF  σε δομή  com.aspose.psd.Rectangle  στρογγυλοποιώντας τις τιμές της  com.aspose.psd.RectangleF  προς τις επόμενες μεγαλύτερες ακέραιες τιμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Η  com.aspose.psd.RectangleF  δομή που θα μετατραπεί. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Το  com.aspose.psd.Point  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το σημείο που αντιπροσωπεύεται από  point  περιέχεται σε αυτή τη  com.aspose.psd.Rectangle  δομή· διαφορετικά false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το  rect  περιέχεται πλήρως μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από  rect  περιέχεται πλήρως σε αυτή τη  com.aspose.psd.Rectangle  δομή· διαφορετικά false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το σημείο που ορίζεται από  x  και  y  περιέχεται σε αυτή τη  com.aspose.psd.Rectangle  δομή· διαφορετικά false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δοκιμάζει εάν το  obj  είναι μια δομή  com.aspose.psd.Rectangle  με την ίδια θέση και μέγεθος με αυτή τη δομή  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το System.Object για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το  obj  είναι μια  com.aspose.psd.Rectangle  δομή και οι ιδιότητες  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , και  com.aspose.psd.Rectangle.Height  είναι ίσες με τις αντίστοιχες ιδιότητες αυτής της  com.aspose.psd.Rectangle  δομής· διαφορετικά, false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Δημιουργεί μια δομή  com.aspose.psd.Rectangle  με τις καθορισμένες θέσεις των άκρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | int | Η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |
| top | int | Η συντεταγμένη y της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |
| right | int | Η συντεταγμένη x της κάτω δεξιάς γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |
| bottom | int | Η συντεταγμένη y της κάτω δεξιάς γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Δημιουργεί ένα νέο  Rectangle  από δύο καθορισμένα σημεία. Οι δύο κατακόρυφες πλευρές του δημιουργημένου  Rectangle  θα είναι ίσες με τα περασμένα  point1  και  point2 . Συνήθως αυτά είναι τα αντίθετα κορυφαία σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Το πρώτο  Point  για το νέο rectangle. |
| point2 | [Point](../../com.aspose.psd/point) | Το δεύτερο  Point  για το νέο rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.Y  και  com.aspose.psd.Rectangle.Height  αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.Rectangle.Y  και του  com.aspose.psd.Rectangle.Height  αυτής της  com.aspose.psd.Rectangle .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Λαμβάνει μια νέα παρουσία της δομής  com.aspose.psd.Rectangle  που έχει τις τιμές  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  και  com.aspose.psd.Rectangle.Height  ορισμένες στο μηδέν.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Το ύψος αυτής της  com.aspose.psd.Rectangle  δομής.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη x της αριστερής άκρης αυτής της  com.aspose.psd.Rectangle  δομής.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.X  και  com.aspose.psd.Rectangle.Width  αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.Rectangle.X  και του  com.aspose.psd.Rectangle.Width  αυτής της  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Λαμβάνει ή ορίζει το μέγεθος αυτής της  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω άκρου αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη y της άνω άκρης αυτής της  com.aspose.psd.Rectangle  δομής.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει το πλάτος αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Το πλάτος αυτής της  com.aspose.psd.Rectangle  δομής.
### getX() {#getX--}
```
public int getX()
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής.
### getY() {#getY--}
```
public int getY()
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Returns:**
int - Η συντεταγμένη y της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη δομή  com.aspose.psd.Rectangle .

**Returns:**
int - Ένας ακέραιος που αντιπροσωπεύει τον κωδικό κατακερματισμού για αυτό το ορθογώνιο.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Δημιουργεί και επιστρέφει ένα διογκωμένο αντίγραφο της καθορισμένης  com.aspose.psd.Rectangle  δομής. Το αντίγραφο διογκώνεται κατά το καθορισμένο ποσό. Η αρχική  com.aspose.psd.Rectangle  δομή παραμένει αμετάβλητη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  με την οποία θα ξεκινήσετε. Αυτό το ορθογώνιο δεν τροποποιείται. |
| x | int | Το ποσό για να διογκώσετε αυτό το  com.aspose.psd.Rectangle  οριζόντια. |
| y | int | Το ποσό για να διογκώσετε αυτό το  com.aspose.psd.Rectangle  κάθετα. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Διογκώνει αυτή τη δομή  com.aspose.psd.Rectangle  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Το ποσό για τη φούσκωση αυτού του rectangle. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Διογκώνει αυτή τη δομή  com.aspose.psd.Rectangle  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το ποσό για να διογκώσετε αυτό το  com.aspose.psd.Rectangle  οριζόντια. |
| ύψος | int | Το ποσό για να διογκώσετε αυτό το  com.aspose.psd.Rectangle  κάθετα. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Αντικαθιστά αυτή τη δομή  com.aspose.psd.Rectangle  με την τομή του εαυτού της και της καθορισμένης δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  με την οποία θα γίνει τομή. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Επιστρέφει μια τρίτη  com.aspose.psd.Rectangle  δομή που αντιπροσωπεύει την τομή δύο άλλων  com.aspose.psd.Rectangle  δομών. Εάν δεν υπάρχει τομή, επιστρέφεται ένα κενό  com.aspose.psd.Rectangle.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Ένα πρώτο rectangle για διατομή. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Ένα δεύτερο rectangle για διατομή. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Καθορίζει εάν αυτό το ορθογώνιο τέμνει το  rect .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Το rectangle για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν υπάρχει οποιαδήποτε τομή, διαφορετικά false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν όλες οι αριθμητικές ιδιότητες αυτής της δομής  com.aspose.psd.Rectangle  έχουν τιμές μηδέν.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν οι ιδιότητες  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , και  com.aspose.psd.Rectangle.Y  αυτού του  com.aspose.psd.Rectangle  έχουν όλες τιμές μηδέν· διαφορετικά, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η  Rectangle  είναι τουλάχιστον εν μέρει ορατή

**Returns:**
boolean -  true  εάν αυτό το  Rectangle  είναι τουλάχιστον εν μέρει ορατό· διαφορετικά,  false .
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Ποσό για μετατόπιση της θέσης. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η οριζόντια μετατόπιση. |
| y | int | Η κάθετη μετατόπιση. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Δοκιμάζει εάν δύο δομές  com.aspose.psd.Rectangle  έχουν ίση θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  δομή που βρίσκεται αριστερά του τελεστή ισότητας. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  δομή που βρίσκεται δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οι δύο  com.aspose.psd.Rectangle  δομές έχουν ίσες τις ιδιότητες  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , και  com.aspose.psd.Rectangle.Height .
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Δοκιμάζει εάν δύο  com.aspose.psd.Rectangle  δομές διαφέρουν σε θέση ή μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  δομή που βρίσκεται αριστερά του τελεστή ανισότητας. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Η  com.aspose.psd.Rectangle  δομή που βρίσκεται δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οποιαδήποτε από τις ιδιότητες  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  ή  com.aspose.psd.Rectangle.Height  των δύο  com.aspose.psd.Rectangle  δομών είναι διαφορετική· διαφορετικά false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Μετατρέπει το καθορισμένο  com.aspose.psd.RectangleF  σε  com.aspose.psd.Rectangle  στρογγυλοποιώντας τις τιμές του  com.aspose.psd.RectangleF  στο πλησιέστερο ακέραιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Το  com.aspose.psd.RectangleF  που θα μετατραπεί. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.Y  και  com.aspose.psd.Rectangle.Height  αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη y που είναι το άθροισμα του  com.aspose.psd.Rectangle.Y  και του  com.aspose.psd.Rectangle.Height  αυτού του  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Λαμβάνει ή ορίζει το ύψος αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το ύψος αυτής της  com.aspose.psd.Rectangle  δομής. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x του αριστερού άκρου αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη x του αριστερού άκρου αυτού του  com.aspose.psd.Rectangle  δομής. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Ένα  Point  που αντιπροσωπεύει την επάνω αριστερή γωνία αυτού του  com.aspose.psd.Rectangle  δομής. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών των ιδιοτήτων  com.aspose.psd.Rectangle.X  και  com.aspose.psd.Rectangle.Width  αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη x που είναι το άθροισμα του  com.aspose.psd.Rectangle.X  και του  com.aspose.psd.Rectangle.Width  αυτού του  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Λαμβάνει ή ορίζει το μέγεθος αυτής της  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Ένα  com.aspose.psd.Size  που αντιπροσωπεύει το πλάτος και το ύψος αυτού του  com.aspose.psd.Rectangle  δομής. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω άκρου αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη y του άνω άκρου αυτού του  com.aspose.psd.Rectangle  δομής. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ορίζει το πλάτος αυτής της  com.aspose.psd.Rectangle  δομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το πλάτος αυτού του  com.aspose.psd.Rectangle  δομής. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας αυτής της δομής  com.aspose.psd.Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η συντεταγμένη y της επάνω αριστερής γωνίας αυτής της  com.aspose.psd.Rectangle  δομής. |

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει τα χαρακτηριστικά αυτής της  com.aspose.psd.Rectangle  σε αναγνώσιμη για άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Μια συμβολοσειρά που περιέχει τη θέση, το πλάτος και το ύψος αυτού του  com.aspose.psd.Rectangle  δομής.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Μετατρέπει το καθορισμένο  com.aspose.psd.RectangleF  σε  com.aspose.psd.Rectangle  περικόπτοντας τις τιμές του  com.aspose.psd.RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Το  com.aspose.psd.RectangleF  που θα μετατραπεί. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Λαμβάνει μια  com.aspose.psd.Rectangle  δομή που περιέχει την ένωση δύο  com.aspose.psd.Rectangle  δομών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Το πρώτο ορθογώνιο για ένωση. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Το δεύτερο ορθογώνιο για ένωση. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

