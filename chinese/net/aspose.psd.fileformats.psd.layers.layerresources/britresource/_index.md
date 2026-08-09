---
title: "类 BritResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource 类。Class BritResource。亮度/对比度调整图层的资源"
type: docs
weight: 2600
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

BritResource 类。亮度/对比度调整图层的资源

```csharp
public class BritResource : AdjustmentLayerResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BritResource](britresource/#constructor)() | 初始化 `BritResource` 类的新实例。 |
| [BritResource](britresource/#constructor_1)(byte[]) | 初始化 `BritResource` 类的新实例。PSD 格式规范包含以下描述：2 亮度 2 对比度 2 亮度和对比度的均值 1 仅实验室颜色。它在现代 PSD（CS5 及以上）中不再使用，取而代之的是 CgEd。CgEd 存储信息属性。 |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | 初始化 `BritResource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | 获取或设置亮度。 |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | 获取或设置对比度。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | 获取或设置一个值，指示是否为 [lab color]。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | 获取图层资源的字节长度。 |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | 获取或设置亮度和对比度的平均值。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | 类型工具信息键。 |

### 另请参阅

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


