---
title: "GradientFillSettings 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | 初始化一个新的 [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | 读/写 | 获取或设置一个值，指示是否 [align with layer]。 |
| 角度 | double | 读/写 | 获取或设置角度。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置颜色。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 获取或设置颜色点。 |
| dither | bool | r/w | 获取或设置一个值，指示此 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) 是否抖动。 |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 填充类型。 |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | 获取此渐变的模式。<br/>            确定 'Gradient Type' = 'Solid/Noise' (0/1)。 |
| gradient_name | 字符串 | 读/写 | 获取或设置渐变的名称。 |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | 获取或设置渐变的类型。 |
| horizontal_offset | double | 读/写 | 获取或设置水平偏移（百分比）。 |
| 插值 | short | 读/写 | 插值。确定平滑度，当 'Gradient Type' = 'Solid' 时。取值范围：0-4096。 |
| reverse | bool | r/w | 获取或设置一个值，指示此 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) 是否反向。 |
| scale | int | 读/写 | 获取或设置比例。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | 获取或设置透明度点。 |
| vertical_offset | double | 读/写 | 获取或设置垂直偏移（百分比）。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | 添加颜色点。 |
| [add_transparency_point()](#add_transparency_point__2) | 添加颜色点。 |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | 生成 LFX2 资源节点。 |
| [remove_color_point(point)](#remove_color_point_point_4) | 移除颜色点。 |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | 移除透明点。 |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

初始化一个新的 [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) 类实例。

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

添加颜色点。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | 已创建颜色点 |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

添加颜色点。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | 已创建透明点 |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

生成 LFX2 资源节点。

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | 生成的 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 列表 |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

移除颜色点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | 该点。 |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

移除透明点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | 该点。 |

