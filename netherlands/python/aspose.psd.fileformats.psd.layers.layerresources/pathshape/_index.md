---
title: "PathShape Klasse"
type: docs
weight: 750
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PathShape()](#PathShape__1) | Initialiseert een nieuw exemplaar van de [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) klasse. |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Initialiseert een nieuw exemplaar van de [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Haalt of stelt een waarde in die aangeeft of dit exemplaar gesloten is. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Haalt of stelt de padbewerkingen (Boolean-bewerkingen) in. |
| shape_index | ushort | r/w | Haalt of stelt de index van de huidige padvorm in de laag in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_items()](#get_items__1) | Haalt array van Bezier-knopen op. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Wijst array van Bezier-knopen toe. |
| [to_vector_path_records()](#to_vector_path_records__3) | Maakt de [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) records aan op basis van dit exemplaar. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Initialiseert een nieuw exemplaar van de [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) klasse.

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Initialiseert een nieuw exemplaar van de [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Het lengte-record. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | De Bezier-knooprecords. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Haalt array van Bezier-knopen op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array van BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Wijst array van Bezier-knopen toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array van bezierknopen |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Maakt de [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) records aan op basis van dit exemplaar.

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Retourneert één [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) en [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) voor elk punt in deze instantie. |


