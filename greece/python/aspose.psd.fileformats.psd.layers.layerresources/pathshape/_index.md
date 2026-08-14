---
title: "Κλάση PathShape"
type: docs
weight: 750
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PathShape()](#PathShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Αποκτά ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες). |
| shape_index | ushort | r/w | Αποκτά ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στη στρώση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_items()](#get_items__1) | Αποκτά πίνακα από κόμβους Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Αναθέτει πίνακα από κόμβους Bezier. |
| [to_vector_path_records()](#to_vector_path_records__3) | Δημιουργεί τις εγγραφές [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) βάσει αυτού του παραδείγματος. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Η εγγραφή μήκους. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Οι εγγραφές κόμβων bezier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Αποκτά πίνακα από κόμβους Bezier.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Πίνακας BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Αναθέτει πίνακα από κόμβους Bezier.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Πίνακας κόμβων Bezier |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Δημιουργεί τις εγγραφές [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) βάσει αυτού του παραδείγματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Επιστρέφει ένα [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) και ένα [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) για κάθε σημείο σε αυτήν την περίπτωση. |


