---
title: "TypeToolInfoResource 类"
type: docs
weight: 1000
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | 初始化 TypeToolInfoResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| a_component | short | 读/写 | 获取或设置 a 组件。 |
| b_component | short | 读/写 | 获取或设置 b 组件。 |
| character_count | int | 读/写 | 获取或设置字符计数。 |
| color_space_value | short | 读/写 | 获取或设置颜色空间值。 |
| font_version | short | 读/写 | 获取或设置字体版本。 |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | 获取或设置字体。 |
| fonts_count | short | r | 获取字体计数。 |
| g_component | short | 读/写 | 获取或设置 g 组件。 |
| horizontal_placement | int | 读/写 | 获取或设置水平位置。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| line_count | short | r | 获取行数。 |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | 获取或设置行。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| r_component | short | 读/写 | 获取或设置 r 组件。 |
| scale_factor | int | 读/写 | 获取或设置比例因子。 |
| selection_end | int | 读/写 | 获取或设置选择结束位置。 |
| selection_start | int | 读/写 | 获取或设置选择起始位置。 |
| signature | int | r | 获取签名。 |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | 获取或设置字体样式。 |
| styles_count | short | r | 获取样式计数。 |
| transform_matrix | double | 读/写 | 获取或设置变换矩阵。 |
| type_value | short | 读/写 | 获取或设置类型值。 |
| version | short | 读/写 | 获取或设置版本。 |
| vertical_placement | int | 读/写 | 获取或设置垂直放置。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 保存指定的流容器。 |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

初始化 TypeToolInfoResource 类的新实例

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

保存指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |

