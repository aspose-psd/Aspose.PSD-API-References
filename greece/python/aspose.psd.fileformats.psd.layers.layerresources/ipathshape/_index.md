---
title: "IPathShape Κλάση"
type: docs
weight: 380
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Λαμβάνει ή ορίζει την ιδιότητα που καθορίζει αν το Shape είναι κλειστό. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Οι λειτουργίες για τον συνδυασμό σχημάτων διαδρομής (Λογικές λειτουργίες). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_items()](#get_items__1) | Αποκτά πίνακα από κόμβους Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Αντιστοιχίζει πίνακα από Bexier κόμπους. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Αποκτά πίνακα από κόμβους Bezier.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Πίνακας του BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Αντιστοιχίζει πίνακα από Bexier κόμπους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Πίνακας κόμβων Bezier |

