---
title: Class BritResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource 班级. 类 BritResource亮度/对比度调整图层资源
type: docs
weight: 2340
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

类 BritResource。亮度/对比度调整图层资源

```csharp
public class BritResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [BritResource](britresource/#constructor)() | 初始化一个新的实例`BritResource`类. |
| [BritResource](britresource/#constructor_1)(byte[]) | 初始化一个新的实例`BritResource`class. PSD 格式规范包含以下描述： 2 Brightness 2 Contrast 2 亮度和对比度的平均值 1 Lab color only 它不用于 CgEd 所在的现代 PSD（CS5 及更高版本）。 CgEd 存储信息 properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | 初始化一个新的实例`BritResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | 获取或设置亮度。 |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | 获取或设置对比度。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | 获取图层资源键。 |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | 获取或设置一个值，指示是否 [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | 获取或设置亮度和对比度的平均值。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | 类型工具信息键。 |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


