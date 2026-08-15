---
title: "Класс PathShape"
type: docs
weight: 750
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PathShape()](#PathShape__1) | Инициализирует новый экземпляр класса [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Инициализирует новый экземпляр класса [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыт ли этот экземпляр. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Получает или задает операции пути (булевы операции). |
| shape_index | ushort | r/w | Получает или задает индекс текущей формы пути в слое. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_items()](#get_items__1) | Получает массив узлов Безье. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Назначает массив узлов Безье. |
| [to_vector_path_records()](#to_vector_path_records__3) | Создает записи [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) на основе этого экземпляра. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Инициализирует новый экземпляр класса [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Инициализирует новый экземпляр класса [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Запись длины. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Записи узлов Безье. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Получает массив узлов Безье.

**Returns**

| Тип | Описание |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Массив BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Назначает массив узлов Безье.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Массив узлов Безье |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Создает записи [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) на основе этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Возвращает один [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) и [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) для каждой точки в этом экземпляре. |


