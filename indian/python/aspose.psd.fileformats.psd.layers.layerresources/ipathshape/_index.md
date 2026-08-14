---
title: "IPathShape क्लास"
type: docs
weight: 380
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Shape को बंद होने का निर्धारण करने वाली property को प्राप्त करता है या सेट करता है। |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | पाथ आकारों को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier नॉट्स की एरे प्राप्त करता है। |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bexier नॉट्स की array को असाइन करता है। |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier नॉट्स की एरे प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord की array। |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bexier नॉट्स की array को असाइन करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | बेज़ियर नॉट्स की सरणी |

