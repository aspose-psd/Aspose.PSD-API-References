---
title: "IPathShape Класс"
type: docs
weight: 380
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Получает или задает свойство, определяющее, закрыта ли Shape. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Операции объединения форм пути (булевы операции). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_items()](#get_items__1) | Получает массив узлов Безье. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Назначает массив узлов Bexier. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Получает массив узлов Безье.

**Returns**

| Тип | Описание |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Массив BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Назначает массив узлов Bexier.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Массив узлов Безье |

