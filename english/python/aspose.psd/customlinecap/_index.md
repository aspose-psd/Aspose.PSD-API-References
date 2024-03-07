---
title: CustomLineCap Class
type: docs
weight: 960
url: /python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class with the specified outline and fill. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class from the specified existing [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration with the specified outline and fill. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class from the specified existing [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration with the specified outline, fill, and inset. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Gets or sets the [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration on which this [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) is based. |
| base_inset | float | r/w | Gets or sets the distance between the cap and the line. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Gets or sets the object that defines the fill for the custom cap. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Gets or sets the [LineJoin](/psd/python-net/aspose.psd/linejoin/) enumeration that determines how lines that compose this [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) object are joined. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Gets or sets the object that defines the outline of the custom cap. |
| width_scale | float | r/w | Gets or sets the amount by which to scale this [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Class object with respect to the width of the  object. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Gets the caps used to start and end lines that make up this custom cap. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Sets the caps used to start and end lines that make up this custom cap. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class with the specified outline and fill.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the fill for the custom cap. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the outline of the custom cap. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class from the specified existing [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration with the specified outline and fill.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the fill for the custom cap. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the outline of the custom cap. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | The line cap from which to create the custom cap. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initializes a new instance of the [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) class from the specified existing [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration with the specified outline, fill, and inset.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the fill for the custom cap. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object that defines the outline of the custom cap. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | The line cap from which to create the custom cap. |
| base_inset | float | The distance between the cap and the line. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Gets the caps used to start and end lines that make up this custom cap.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | The [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration used at the beginning of a line within this cap. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | The [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration used at the end of a line within this cap. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Sets the caps used to start and end lines that make up this custom cap.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | The [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration used at the beginning of a line within this cap. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | The [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration used at the end of a line within this cap. |

