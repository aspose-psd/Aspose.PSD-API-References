---
title: "PathShape"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το σχήμα από τους κόμβους της καμπύλης Bezier."
type: docs
weight: 16
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

Το σχήμα από τους κόμβους της καμπύλης Bezier.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PathShape()](#PathShape--) | Αρχικοποιεί ένα νέο παράδειγμα της [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) κλάσης. |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Αρχικοποιεί ένα νέο παράδειγμα της [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Λαμβάνει τον πίνακα των κόμβων Bezier. |
| [getPathOperations()](#getPathOperations--) | Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες). |
| [getShapeIndex()](#getShapeIndex--) | Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στο επίπεδο. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Αναθέτει πίνακα από κόμβους Bezier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στο επίπεδο. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Δημιουργεί τις εγγραφές  VectorPathRecord  βάσει αυτής της παρουσίας. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Αρχικοποιεί ένα νέο παράδειγμα της [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) κλάσης.

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Αρχικοποιεί ένα νέο παράδειγμα της [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | Η εγγραφή μήκους. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Οι εγγραφές κόμβων bezier. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


Λαμβάνει τον πίνακα των κόμβων Bezier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Πίνακας των BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στο επίπεδο.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή.

Τιμή:  true  εάν αυτή η παρουσία είναι κλειστή· διαφορετικά,  false .

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




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή.

Τιμή:  true  εάν αυτή η παρουσία είναι κλειστή· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Αναθέτει πίνακα από κόμβους Bezier.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Πίνακας από κόμβους bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στο επίπεδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


Δημιουργεί τις εγγραφές  VectorPathRecord  βάσει αυτής της παρουσίας.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Επιστρέφει ένα  LengthRecord  και  BezierKnotRecord  για κάθε σημείο σε αυτήν την παρουσία.
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

