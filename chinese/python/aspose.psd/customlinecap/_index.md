---
title: "CustomLineCap 类"
type: docs
weight: 1010
url: /zh/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | 使用指定的轮廓和填充初始化 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类的新实例。 |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | 使用指定的现有 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举，从中初始化 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类的新实例，并指定轮廓和填充。 |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | 初始化一个新的 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类实例，使用指定的现有 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举以及指定的轮廓、填充和内嵌。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 获取或设置此 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 所基于的 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举。 |
| base_inset | float | 读/写 | 获取或设置帽子与线之间的距离。 |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | 获取或设置定义自定义帽子填充的对象。 |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | 获取或设置决定组成此 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 对象的线段如何连接的 [LineJoin](/psd/python-net/aspose.psd/linejoin/) 枚举。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | 获取或设置定义自定义帽子轮廓的对象。 |
| width_scale | float | r/w | 获取或设置相对于对象宽度缩放此 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类对象的比例。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | 获取用于开始和结束构成此自定义帽子的线段的帽子。 |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | 设置用于开始和结束构成此自定义帽子的线段的帽子。 |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

使用指定的轮廓和填充初始化 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子填充的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

使用指定的现有 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举，从中初始化 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类的新实例，并指定轮廓和填充。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子填充的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 用于创建自定义帽子的线帽。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

初始化一个新的 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 类实例，使用指定的现有 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举以及指定的轮廓、填充和内嵌。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子填充的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象。 |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 用于创建自定义帽子的线帽。 |
| base_inset | float | 帽子与线之间的距离。 |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

获取用于开始和结束构成此自定义帽子的线段的帽子。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | 此帽子内线段起始处使用的 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举。 |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | 此帽子内线段结束处使用的 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举。 |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

设置用于开始和结束构成此自定义帽子的线段的帽子。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 此帽子内线段起始处使用的 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 此帽子内线段结束处使用的 [LineCap](/psd/python-net/aspose.psd/linecap/) 枚举。 |

