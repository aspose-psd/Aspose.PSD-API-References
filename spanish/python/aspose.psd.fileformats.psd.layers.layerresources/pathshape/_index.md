---
title: "Clase PathShape"
type: docs
weight: 750
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PathShape()](#PathShape__1) | Inicializa una nueva instancia de la clase [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Inicializa una nueva instancia de la clase [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si esta instancia está cerrada. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Obtiene o establece las operaciones de ruta (operaciones booleanas). |
| shape_index | ushort | r/w | Obtiene o establece el índice de la forma de ruta actual en la capa. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_items()](#get_items__1) | Obtiene una matriz de nudos Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Asigna una matriz de nudos Bezier. |
| [to_vector_path_records()](#to_vector_path_records__3) | Crea los registros [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basados en esta instancia. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Inicializa una nueva instancia de la clase [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Inicializa una nueva instancia de la clase [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | El registro de longitud. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Los registros de nudos Bezier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Obtiene una matriz de nudos Bezier.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Matriz de BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Asigna una matriz de nudos Bezier.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Matriz de nudos Bézier |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Crea los registros [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basados en esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Devuelve un [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) y un [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) para cada punto en esta instancia. |


