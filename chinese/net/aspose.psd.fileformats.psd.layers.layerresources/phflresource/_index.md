---
title: Class PhflResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource 班级. PhflResource 类 Resource of Exposure Adjustment Layer 2 Version   3  or   2  12 4 bytes each for XYZ colorOnly in Version 3 10 2 bytes color space followed by 4  2 bytes color componentOnly in Version 2 4 密度 1 保持亮度
type: docs
weight: 2890
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 获取或设置密度。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | 获取图层资源键。 |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 获取或设置一个值，指示是否[保持亮度]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | 获取版本。默认为 2 或 3 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | 获取RGB的颜色。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | 设置 RGB 颜色。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | 类型工具信息键。 |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


