---
title: "Κλάση Rectangle"
type: docs
weight: 3810
url: /el/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/) με την καθορισμένη θέση και μέγεθος. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/) με την καθορισμένη θέση και μέγεθος. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bottom | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη y που είναι το άθροισμα των τιμών ιδιοτήτων [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) και [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει ένα νέο στιγμιότυπο της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/) που έχει τις τιμές [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) και [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) ορισμένες στο μηδέν. |
| height | int | r/w | Λαμβάνει ή ορίζει το ύψος αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν όλες οι αριθμητικές ιδιότητες αυτής της [Rectangle](/psd/python-net/aspose.psd/rectangle/) έχουν τιμές μηδέν. |
| left | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Λαμβάνει ή ορίζει τις συντεταγμένες της επάνω αριστερής γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη x που είναι το άθροισμα των τιμών ιδιοτήτων [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) και [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Λαμβάνει ή ορίζει το μέγεθος αυτής της [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω άκρης αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | Λαμβάνει ή ορίζει το πλάτος αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Μετατρέπει τη συγκεκριμένη δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) στρογγυλοποιώντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/) προς τα επόμενα μεγαλύτερα ακέραια. |
| [contains(point)](#contains_point_2) | Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από <paramref name="rect" /> περιέχεται πλήρως μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Δημιουργεί μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) με τις καθορισμένες θέσεις των άκρων. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Δημιουργεί ένα νέο [Rectangle](/psd/python-net/aspose.psd/rectangle/) από δύο καθορισμένα σημεία. Οι δύο κατακόρυφες πλευρές του δημιουργημένου [Rectangle](/psd/python-net/aspose.psd/rectangle/) θα είναι ίσες με τα περασμένα <paramref name="point1" /> και <paramref name="point2" />. Αυτά θα είναι συνήθως τα αντίθετα κορυφαία σημεία. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Δημιουργεί και επιστρέφει ένα φουσκωτό αντίγραφο της καθορισμένης δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). Το αντίγραφο φουσκώνεται κατά το καθορισμένο ποσό. Η αρχική δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) παραμένει αμετάβλητη. |
| [inflate(size)](#inflate_size_8) | Μεγεθύνει αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) κατά το καθορισμένο ποσό. |
| [inflate(width, height)](#inflate_width_height_9) | Μεγεθύνει αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) κατά το καθορισμένο ποσό. |
| [intersect(a, b)](#intersect_a_b_10) | Επιστρέφει μια τρίτη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει τη διατομή δύο άλλων δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/). Εάν δεν υπάρχει διατομή, επιστρέφεται ένα κενό [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersect(rect)](#intersect_rect_11) | Αντικαθιστά αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) με τη διατομή του με τον καθορισμένο [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Καθορίζει εάν αυτό το ορθογώνιο τέμνει το <paramref name="rect" />. |
| normalize() | Κανονικοποιεί το ορθογώνιο κάνοντας το πλάτος και το ύψος του θετικά, το αριστερό μικρότερο από το δεξί και το πάνω μικρότερο από το κάτω. |
| [offset(pos)](#offset_pos_13) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [offset(x, y)](#offset_x_y_14) | Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό. |
| [round(value)](#round_value_15) | Μετατρέπει το καθορισμένο [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/) στρογγυλοποιώντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/) στο πλησιέστερο ακέραιο. |
| [truncate(value)](#truncate_value_16) | Μετατρέπει το καθορισμένο [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/) περικόπτοντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | Αποκτά μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που περιέχει την ένωση δύο δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/) με την καθορισμένη θέση και μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Ένα [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει την επάνω αριστερή γωνία της ορθογώνιας περιοχής. |
| size | [Size](/psd/python-net/aspose.psd/size) | Ένα [Size](/psd/python-net/aspose.psd/size/) που αντιπροσωπεύει το πλάτος και το ύψος της ορθογώνιας περιοχής. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/) με την καθορισμένη θέση και μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x της πάνω αριστερής γωνίας του ορθογωνίου. |
| y | int | Η συντεταγμένη y της πάνω αριστερής γωνίας του ορθογωνίου. |
| width | int | Το πλάτος του ορθογωνίου. |
| height | int | Το ύψος του ορθογωνίου. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Μετατρέπει τη συγκεκριμένη δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) στρογγυλοποιώντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/) προς τα επόμενα μεγαλύτερα ακέραια.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Η δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που θα μετατραπεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Επιστρέφει ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Το [Point](/psd/python-net/aspose.psd/point/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το σημείο που αντιπροσωπεύεται από <paramref name="point" /> περιέχεται σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/); διαφορετικά false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από <paramref name="rect" /> περιέχεται πλήρως μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το [Rectangle](/psd/python-net/aspose.psd/rectangle/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από <paramref name="rect" /> περιέχεται πλήρως σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/); διαφορετικά false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το σημείο που ορίζεται από <paramref name="x" /> και <paramref name="y" /> περιέχεται σε αυτή τη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/); διαφορετικά false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Δημιουργεί μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) με τις καθορισμένες θέσεις των άκρων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| left | int | Η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | Η συντεταγμένη y της επάνω αριστερής γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | Η συντεταγμένη x της κάτω δεξιάς γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | Η συντεταγμένη y της κάτω δεξιάς γωνίας αυτής της δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το νέο [Rectangle](/psd/python-net/aspose.psd/rectangle/) που δημιουργεί αυτή η μέθοδος. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Δημιουργεί ένα νέο [Rectangle](/psd/python-net/aspose.psd/rectangle/) από δύο καθορισμένα σημεία. Οι δύο κατακόρυφες πλευρές του δημιουργημένου [Rectangle](/psd/python-net/aspose.psd/rectangle/) θα είναι ίσες με τα περασμένα <paramref name="point1" /> και <paramref name="point2" />. Αυτά θα είναι συνήθως τα αντίθετα κορυφαία σημεία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Το πρώτο [Point](/psd/python-net/aspose.psd/point/) για το νέο ορθογώνιο. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Το δεύτερο [Point](/psd/python-net/aspose.psd/point/) για το νέο ορθογώνιο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα νεοδημιουργημένο [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Δημιουργεί και επιστρέφει ένα φουσκωτό αντίγραφο της καθορισμένης δομής [Rectangle](/psd/python-net/aspose.psd/rectangle/). Το αντίγραφο φουσκώνεται κατά το καθορισμένο ποσό. Η αρχική δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) παραμένει αμετάβλητη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το [Rectangle](/psd/python-net/aspose.psd/rectangle/) με το οποίο ξεκινάτε. Αυτό το rectangle δεν τροποποιείται. |
| x | int | Το ποσό για την οριζόντια μεγέθυνση αυτού του [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | Το ποσό για την κάθετη μεγέθυνση αυτού του [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το μεγεθυμένο [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Μεγεθύνει αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) κατά το καθορισμένο ποσό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Το ποσό για την επέκταση αυτού του ορθογωνίου. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Μεγεθύνει αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) κατά το καθορισμένο ποσό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το ποσό για την οριζόντια μεγέθυνση αυτού του [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| height | int | Το ποσό για την κάθετη μεγέθυνση αυτού του [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Επιστρέφει μια τρίτη δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει τη διατομή δύο άλλων δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/). Εάν δεν υπάρχει διατομή, επιστρέφεται ένα κενό [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα πρώτο ορθογώνιο για τομή. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα δεύτερο ορθογώνιο για τομή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει τη διατομή του <paramref name="a" /> και του <paramref name="b" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Αντικαθιστά αυτό το [Rectangle](/psd/python-net/aspose.psd/rectangle/) με τη διατομή του με τον καθορισμένο [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το [Rectangle](/psd/python-net/aspose.psd/rectangle/) με το οποίο να διασταυρωθεί. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Καθορίζει εάν αυτό το ορθογώνιο τέμνει το <paramref name="rect" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν υπάρχει οποιαδήποτε τομή, διαφορετικά false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Ποσό για μετατόπιση της θέσης. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Ρυθμίζει τη θέση αυτού του ορθογωνίου κατά το καθορισμένο ποσό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η οριζόντια μετατόπιση. |
| y | int | Η κάθετη μετατόπιση. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Μετατρέπει το καθορισμένο [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/) στρογγυλοποιώντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/) στο πλησιέστερο ακέραιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που θα μετατραπεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα νέο [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Μετατρέπει το καθορισμένο [RectangleF](/psd/python-net/aspose.psd/rectanglef/) σε ένα [Rectangle](/psd/python-net/aspose.psd/rectangle/) περικόπτοντας τις τιμές του [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που θα μετατραπεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα νέο [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Αποκτά μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που περιέχει την ένωση δύο δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα πρώτο ορθογώνιο για ένωση. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ένα δεύτερο ορθογώνιο για ένωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που περιορίζει την ένωση των δύο δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


