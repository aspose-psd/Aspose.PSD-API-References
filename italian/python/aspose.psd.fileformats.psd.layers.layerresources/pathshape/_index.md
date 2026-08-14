---
title: "PathShape Classe"
type: docs
weight: 750
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathShape()](#PathShape__1) | Inizializza una nuova istanza della classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Inizializza una nuova istanza della classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è chiusa. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Ottiene o imposta le operazioni di percorso (operazioni booleane). |
| shape_index | ushort | r/w | Ottiene o imposta l'indice della forma di percorso corrente nel livello. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | Ottiene l'array di nodi Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Assegna l'array di nodi Bezier. |
| [to_vector_path_records()](#to_vector_path_records__3) | Crea i record [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basati su questa istanza. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Inizializza una nuova istanza della classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Inizializza una nuova istanza della classe [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Il record di lunghezza. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | I record dei nodi bezier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Ottiene l'array di nodi Bezier.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array di BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Assegna l'array di nodi Bezier.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array di nodi Bézier |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Crea i record [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basati su questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Restituisce un [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) e un [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) per ogni punto in questa istanza. |


