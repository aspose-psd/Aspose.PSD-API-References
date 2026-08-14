---
title: "Κλάση SizeF"
type: docs
weight: 4090
url: /el/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [SizeF()](#SizeF__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SizeF |
| [SizeF(point)](#SizeF_point_2) | Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το καθορισμένο [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το καθορισμένο [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από τις καθορισμένες διαστάσεις. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Λαμβάνει ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) που έχει τις τιμές [SizeF.width](/psd/python-net/aspose.psd/sizef/) και [SizeF.height](/psd/python-net/aspose.psd/sizef/) ορισμένες στο μηδέν. |
| height | float | r/w | Λαμβάνει ή ορίζει το κάθετο συστατικό αυτού του [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [SizeF](/psd/python-net/aspose.psd/sizef/) έχει μηδενικό πλάτος και ύψος. |
| width | float | r/w | Λαμβάνει ή ορίζει το οριζόντιο συστατικό αυτού του [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](/psd/python-net/aspose.psd/sizef/) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [to_point_f()](#to_point_f__3) | Μετατρέπει ένα [SizeF](/psd/python-net/aspose.psd/sizef/) σε ένα [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Μετατρέπει ένα [SizeF](/psd/python-net/aspose.psd/sizef/) σε μια δομή [Size](/psd/python-net/aspose.psd/size/) με περικομμένες τιμές μεγέθους. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το καθορισμένο [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Το [PointF](/psd/python-net/aspose.psd/pointf/) από το οποίο θα αρχικοποιηθεί αυτό το [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το καθορισμένο [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Το [SizeF](/psd/python-net/aspose.psd/sizef/) από το οποίο θα δημιουργηθεί το νέο [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Αρχικοποιεί ένα νέο αντικείμενο της δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από τις καθορισμένες διαστάσεις.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | float | Το συστατικό πλάτους του νέου [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Το συστατικό ύψους του νέου [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](/psd/python-net/aspose.psd/sizef/) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Το πρώτο [SizeF](/psd/python-net/aspose.psd/sizef/) για προσθήκη. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Το δεύτερο [SizeF](/psd/python-net/aspose.psd/sizef/) για προσθήκη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Μια [SizeF](/psd/python-net/aspose.psd/sizef/) δομή που είναι το αποτέλεσμα της πράξης πρόσθεσης. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](/psd/python-net/aspose.psd/sizef/) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Η [SizeF](/psd/python-net/aspose.psd/sizef/) δομή στην αριστερή πλευρά του τελεστή αφαίρεσης. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Η [SizeF](/psd/python-net/aspose.psd/sizef/) δομή στη δεξιά πλευρά του τελεστή αφαίρεσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Η [SizeF](/psd/python-net/aspose.psd/sizef/) που είναι το αποτέλεσμα της πράξης αφαίρεσης. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Μετατρέπει ένα [SizeF](/psd/python-net/aspose.psd/sizef/) σε ένα [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Επιστρέφει μια [PointF](/psd/python-net/aspose.psd/pointf/) δομή. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Μετατρέπει ένα [SizeF](/psd/python-net/aspose.psd/sizef/) σε μια δομή [Size](/psd/python-net/aspose.psd/size/) με περικομμένες τιμές μεγέθους.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Επιστρέφει μια [Size](/psd/python-net/aspose.psd/size/) δομή. |


