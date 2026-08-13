---
title: "VstkResource 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | 初始化 VstkResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| fill_enabled | bool | 读/写 | 获取或设置指示是否启用笔画填充的值。 |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | 获取或设置 Stroke 的填充设置。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
| stroke_enabled | bool | 读/写 | 获取或设置指示是否启用笔画效果的值。 |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | 获取或设置笔画混合模式。 |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | 获取或设置笔画实体。属性决定笔画的填充设置。 |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | 获取或设置 Stroke 样式线对齐方式。 |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | 获取或设置笔画样式线帽的类型。 |
| stroke_style_line_cap_width | double | 读/写 | 获取或设置笔画线帽宽度。 |
| stroke_style_line_dash_offset | int | 读/写 | 获取或设置笔画样式线段偏移。 |
| stroke_style_line_dash_set | double | 读/写 | 获取或设置线段虚线数组。 |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | 获取或设置笔画样式线段连接类型。 |
| stroke_style_line_width | double | 读/写 | 获取或设置笔画线宽。 |
| stroke_style_miter_limit | double | 读/写 | 获取或设置笔画样式斜接限制。 |
| stroke_style_opacity | int | 读/写 | 获取或设置笔画样式不透明度（0-100%）。 |
| stroke_style_resolution | double | 读/写 | 获取或设置笔画样式分辨率。 |
| stroke_style_scale_lock | bool | 读/写 | 获取或设置笔画样式比例锁定。 |
| stroke_style_stroke_adjust | bool | 读/写 | 获取或设置笔画调整。 |
| stroke_style_version | int | 读/写 | 获取或设置笔画样式版本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

初始化 VstkResource 类的新实例

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

