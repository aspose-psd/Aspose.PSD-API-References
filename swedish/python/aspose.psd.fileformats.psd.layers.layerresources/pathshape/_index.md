---
title: "PathShape klass"
type: docs
weight: 750
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PathShape()](#PathShape__1) | Initierar en ny instans av klassen [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Initierar en ny instans av klassen [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta objekt är stängt. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Hämtar eller anger sökvägsoperationerna (booleska operationer). |
| shape_index | ushort | r/w | Hämtar eller anger indexet för den aktuella sökvägsformen i lagret. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_items()](#get_items__1) | Hämtar en array av Bezier-knutar. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Tilldelar en array av Bezier-knutar. |
| [to_vector_path_records()](#to_vector_path_records__3) | Skapar [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) poster baserat på detta objekt. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Initierar en ny instans av klassen [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Initierar en ny instans av klassen [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Längdposten. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier-knutposterna. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Hämtar en array av Bezier-knutar.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array av BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Tilldelar en array av Bezier-knutar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array av bezier-knutar |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Skapar [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) poster baserat på detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Returnerar en [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) och en [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) för varje punkt i detta objekt. |


