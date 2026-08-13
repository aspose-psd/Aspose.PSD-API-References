---
title: "ColorantLab 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Summary:** Represents LAB Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantLab

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantLab()](#ColorantLab__1) | 初始化一个新的 [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) 类实例。 |
| [ColorantLab(a, b, l)](#ColorantLab_a_b_l_2) | 初始化一个新的 [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MAX_A [static] | int | r | 最大 A 组件值 |
| MAX_B [static] | int | r | 最大 A 组件值 |
| MAX_L [static] | float | r | 最大 A 组件值 |
| MIN_A [static] | int | r | 最小 A 组件值 |
| MIN_B [static] | int | r | 最小 B 组件值 |
| MIN_L [static] | float | r | 最小 L 组件值 |
| a | int | 读/写 | 获取或设置 A 组件。 |
| b | int | 读/写 | 获取或设置 B 组件。 |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | 获取或设置颜色的类型。 |
| l | float | 读/写 | 获取或设置 L 组件。 |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | 获取 [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/)。 |
| namespace_uri | 字符串 | r | 获取默认的命名空间 URI。 |
| 前缀 | 字符串 | r | 获取前缀。 |
| swatch_name | 字符串 | 读/写 | 获取或设置色板的名称。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: ColorantLab() {#ColorantLab__1}


```
 ColorantLab() 
```

初始化一个新的 [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) 类实例。

### Constructor: ColorantLab(a, b, l) {#ColorantLab_a_b_l_2}


```
 ColorantLab(a, b, l) 
```

初始化一个新的 [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| a | int | A 组件。 |
| b | int | B 组件。 |
| l | float | L 组件。 |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

获取 XMP 格式中包含的字符串值。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回 XMP 格式中包含的字符串值。 |


