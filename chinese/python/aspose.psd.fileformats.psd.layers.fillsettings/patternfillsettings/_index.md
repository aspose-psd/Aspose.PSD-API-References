---
title: "PatternFillSettings 类"
type: docs
weight: 130
url: /zh/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | 初始化一个新的 PatternFillSettings 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | 读/写 | 获取或设置一个值，指示是否 [link with layer]。 |
| 角度 | double | 读/写 | 获取或设置角度。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置颜色。 |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 填充类型 |
| horizontal_offset | int | 读/写 | 获取或设置水平偏移。 |
| linked | bool | r/w | 获取或设置一个值，指示此 [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) 是否已链接。 |
| pattern_data | int | 读/写 | 获取或设置图案数据。 |
| pattern_height | int | 读/写 | 获取或设置图案的高度。 |
| pattern_id | 字符串 | 读/写 | 获取或设置图案标识符。 |
| pattern_name | 字符串 | 读/写 | 获取或设置图案的名称。 |
| pattern_width | int | 读/写 | 获取或设置图案的宽度。 |
| point_type | 字符串 | 读/写 | 获取或设置点的类型。 |
| scale | double | 读/写 | 获取或设置比例。 |
| vertical_offset | int | 读/写 | 获取或设置垂直偏移量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | 生成 LFX2 资源节点。 |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

初始化一个新的 PatternFillSettings 类实例。

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

生成 LFX2 资源节点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point_type | 字符串 | 点的类型。 |
| color | [Color](/psd/python-net/aspose.psd/color) | 颜色。 |
| pattern_name | 字符串 | 图案的名称。 |
| 标识符 | 字符串 | 标识符。 |
| scale | double | 比例。 |
| 已链接 | bool | 如果设置为 <c>true</c> [已链接]。 |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | 偏移量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | 列表 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


