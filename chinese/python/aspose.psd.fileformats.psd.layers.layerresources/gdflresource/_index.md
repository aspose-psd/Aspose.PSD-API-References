---
title: "GdFlResource 类"
type: docs
weight: 330
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | 初始化 GdFlResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| align_with_layer | bool | 读/写 | 获取或设置一个值，指示是否 [align with layer]。 |
| 角度 | double | 读/写 | 获取或设置角度。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取 RGB 的颜色。 |
| color_model | 字符串 | 读/写 | 颜色模型 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 获取颜色点。 |
| dither | bool | r/w | 获取或设置一个值，指示此 [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) 是否为抖动。 |
| gradient_interval | double | 读/写 | 获取或设置渐变间隔。 |
| gradient_mode | 字符串 | 读/写 | 此渐变的模式。<br/>            确定 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs"。 |
| gradient_name | 字符串 | 读/写 | 获取或设置渐变的名称。 |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | 获取或设置渐变的类型。 |
| horizontal_offset | double | 读/写 | 获取或设置水平偏移。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat 的最大颜色。 |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat 的最小颜色。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| reverse | bool | r/w | 获取或设置一个值，指示此 [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) 是否为反向。 |
| rnd_number_seed | int | 读/写 | 用于为噪声渐变生成颜色的随机数种子。 |
| roughness | int | 读/写 | 粗糙度因子。 |
| scale | int | 读/写 | 获取或设置比例。 |
| show_transparency | bool | 读/写 | 显示透明度的标志。 |
| signature | int | r | 获取签名。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 获取透明点。 |
| use_vector_color | bool | 读/写 | 使用矢量颜色的标志。 |
| vertical_offset | double | 读/写 | 获取或设置垂直偏移量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

初始化 GdFlResource 类的新实例

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

