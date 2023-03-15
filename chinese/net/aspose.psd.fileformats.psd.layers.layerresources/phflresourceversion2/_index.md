---
title: Class PhflResourceVersion2
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 班级. PhflResource 类 Resource of Exposure Adjustment Layer 2 Version   3  or   2  12 4 bytes each for XYZ colorOnly in Version 3 10 2 bytes color space followed by 4  2 bytes color componentOnly in Version 2 4 密度 1 保持亮度
type: docs
weight: 2900
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
## PhflResourceVersion2 class

PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度

```csharp
public class PhflResourceVersion2 : PhflResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | 初始化一个新的实例`PhflResourceVersion2`类. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | 初始化一个新的实例`PhflResourceVersion2`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | 获取颜色空间。 |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | 获取或设置color 的A分量 |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | 获取或设置 B 分量 |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | 获取或设置 color 的 L 分量 |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 获取或设置密度。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 获取或设置一个值，指示是否[保持亮度]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | 获取版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | 获取颜色。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | 设置 RGB 颜色。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


