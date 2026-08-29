---
title: "IPathShape"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το Shape από τους κόμβους της καμπύλης Bezier."
type: docs
weight: 31
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Το Shape από τους κόμβους της καμπύλης Bezier.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getItems()](#getItems--) | Λαμβάνει τον πίνακα των κόμβων Bezier. |
| [getPathOperations()](#getPathOperations--) | Οι λειτουργίες για το συνδυασμό σχημάτων διαδρομής (Λογικές πράξεις). |
| [isClosed()](#isClosed--) | Λαμβάνει ή ορίζει την ιδιότητα που καθορίζει εάν το Σχήμα είναι κλειστό. |
| [setClosed(boolean value)](#setClosed-boolean-) | Λαμβάνει ή ορίζει την ιδιότητα που καθορίζει εάν το Σχήμα είναι κλειστό. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Αναθέτει έναν πίνακα κόμβων Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Οι λειτουργίες για το συνδυασμό σχημάτων διαδρομής (Λογικές πράξεις). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Λαμβάνει τον πίνακα των κόμβων Bezier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Πίνακας BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Οι λειτουργίες για το συνδυασμό σχημάτων διαδρομής (Λογικές πράξεις).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Λαμβάνει ή ορίζει την ιδιότητα που καθορίζει εάν το Σχήμα είναι κλειστό.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Λαμβάνει ή ορίζει την ιδιότητα που καθορίζει εάν το Σχήμα είναι κλειστό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Αναθέτει έναν πίνακα κόμβων Bexier.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Πίνακας από κόμβους bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Οι λειτουργίες για το συνδυασμό σχημάτων διαδρομής (Λογικές πράξεις).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

