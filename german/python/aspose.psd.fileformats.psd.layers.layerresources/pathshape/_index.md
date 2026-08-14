---
title: "PathShape Klasse"
type: docs
weight: 750
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PathShape()](#PathShape__1) | Initialisiert eine neue Instanz der Klasse [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Initialisiert eine neue Instanz der Klasse [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz geschlossen ist. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Liest oder setzt die Pfadoperationen (Boolesche Operationen). |
| shape_index | ushort | r/w | Liest oder setzt den Index der aktuellen Pfadform in der Ebene. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_items()](#get_items__1) | Liest ein Array von Bézier-Knoten. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Weist ein Array von Bézier-Knoten zu. |
| [to_vector_path_records()](#to_vector_path_records__3) | Erstellt die [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) Datensätze basierend auf dieser Instanz. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Initialisiert eine neue Instanz der Klasse [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Initialisiert eine neue Instanz der Klasse [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Der Längendatensatz. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Die Bezier-Knoten-Datensätze. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Liest ein Array von Bézier-Knoten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array von BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Weist ein Array von Bézier-Knoten zu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array von Bezier-Knoten |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Erstellt die [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) Datensätze basierend auf dieser Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Gibt einen [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) und einen [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) für jeden Punkt in dieser Instanz zurück. |


