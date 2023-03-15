---
title: Class PhflResourceVersion3
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 班级. PhflResource 类 Resource of Exposure Adjustment Layer 2 Version   3  or   2  12 4 bytes each for XYZ colorOnly in Version 3 10 2 bytes color space followed by 4  2 bytes color componentOnly in Version 2 4 密度 1 保持亮度
type: docs
weight: 2910
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
## PhflResourceVersion3 class

PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度

```csharp
public class PhflResourceVersion3 : PhflResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | 初始化一个新的实例`PhflResourceVersion3`类. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | 初始化一个新的实例`PhflResourceVersion3`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | 获取颜色空间。 |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | 获取或设置 X 颜色。 |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | 获取或设置 Y 颜色。 |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | 获取或设置 Z 颜色。 |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 获取或设置密度。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 获取或设置一个值，指示是否[保持亮度]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | 获取版本。默认为 2 或 3 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | 获取颜色。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | 设置 RGB 颜色。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


