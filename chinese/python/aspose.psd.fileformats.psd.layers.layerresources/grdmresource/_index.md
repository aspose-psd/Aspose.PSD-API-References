---
title: "GrdmResource 类"
type: docs
weight: 340
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | 初始化 [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| color_model | short | 读/写 | 颜色模型。<br/> 当 'Gradient type' = 'Noise' 时，我们可以将 'Color Model' 设为 RGB/SHB/LAB (3/4/6)。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 获取或设置颜色点。 |
| 抖动 | bool | 读/写 | 是否对梯度进行抖动。 |
| expansion_count | short | 读/写 | 扩展计数 ( = 2 for Photoshop 6.0)。 |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | 此梯度的模式<br/> 确定 'Gradient Type' = 'Solid/Noise' (0/1)。 |
| gradient_name | 字符串 | 读/写 | 梯度的名称：Unicode 字符串，已填充。 |
| 插值 | short | 读/写 | 插值。确定平滑度，当 'Gradient Type' = 'Solid' (GradientMode = 0) 时。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp 格式的最大颜色。<br/> 颜色具有 ARGB 通道，每个通道为 16 位。 |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp 格式的最小颜色。<br/> 颜色具有 ARGB 通道，每个通道为 16 位。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| 反转 | bool | 读/写 | 梯度是否已反转。 |
| rnd_number_seed | int | 读/写 | 用于为噪声渐变生成颜色的随机数种子。 |
| roughness | int | 读/写 | 粗糙度因子<br/> 当 'Gradient type' = 'Noise' 时，我们可以设置 'Roughness' (0 - 2048)。 |
| show_transparency | short | 读/写 | 显示透明度的标志<br/> 当 'Gradient type' = 'Noise' 时，我们可以将 'Add transparency' 设为 true。 |
| signature | int | r | 获取签名。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 获取或设置透明度点。 |
| use_vector_color | short | 读/写 | 使用矢量颜色的标志。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源数据保存到指定的流容器。 |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

初始化 [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| psd_version | int | 资源的 psd 版本。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将资源数据保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |

