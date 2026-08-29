---
title: "Classe PathShape"
type: docs
weight: 750
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathShape()](#PathShape__1) | Initialise une nouvelle instance de la classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Initialise une nouvelle instance de la classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Obtient ou définit les opérations de chemin (opérations booléennes). |
| shape_index | ushort | r/w | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | Obtient le tableau de nœuds de Bézier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Assigne le tableau de nœuds de Bézier. |
| [to_vector_path_records()](#to_vector_path_records__3) | Crée les enregistrements [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basés sur cette instance. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Initialise une nouvelle instance de la classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Initialise une nouvelle instance de la classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | L'enregistrement de longueur. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Les enregistrements de nœuds de Bézier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Obtient le tableau de nœuds de Bézier.

**Returns**

| Type | Description |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Tableau de BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Assigne le tableau de nœuds de Bézier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Tableau de nœuds Bézier |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Crée les enregistrements [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basés sur cette instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Renvoie un [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) et un [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) pour chaque point de cette instance. |


