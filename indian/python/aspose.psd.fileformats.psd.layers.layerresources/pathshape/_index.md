---
title: "PathShape क्लास"
type: docs
weight: 750
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PathShape()](#PathShape__1) | नया उदाहरण प्रारंभ करता है [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) क्लास। |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | नया उदाहरण प्रारंभ करता है [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण बंद है या नहीं। |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | पाथ ऑपरेशन्स (बूलियन ऑपरेशन्स) को प्राप्त करता है या सेट करता है। |
| shape_index | ushort | r/w | लेयर में वर्तमान पाथ शेप का इंडेक्स प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier नॉट्स की एरे प्राप्त करता है। |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bezier नॉट्स की एरे असाइन करता है। |
| [to_vector_path_records()](#to_vector_path_records__3) | इस उदाहरण के आधार पर [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) रिकॉर्ड बनाता है। |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

नया उदाहरण प्रारंभ करता है [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) क्लास।

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

नया उदाहरण प्रारंभ करता है [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | लंबाई रिकॉर्ड। |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | bezier नॉट रिकॉर्ड। |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier नॉट्स की एरे प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord की एरे |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bezier नॉट्स की एरे असाइन करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | बेज़ियर नॉट्स की सरणी |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

इस उदाहरण के आधार पर [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) रिकॉर्ड बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | इस उदाहरण में प्रत्येक बिंदु के लिए एक [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) और एक [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) लौटाता है। |


