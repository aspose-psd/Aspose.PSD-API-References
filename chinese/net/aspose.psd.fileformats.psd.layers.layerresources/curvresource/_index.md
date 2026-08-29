---
title: "类 CurvResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource 类。CurvResource 类。曲线调整图层的资源。1 字节 - 0 表示使用曲线，1 表示在映射上使用像素；如果为 0，则后面跟 2 字节 short，默认值为 1。4 字节 - int，仅使用最后一个字节的位。第一位对应 1 通道，第四位对应 4 通道，例如 2 字节 short 表示点数，4 字节 表示点的数量，曲线的点由 2 个 short（第一个位置，第二个高度）组成，4 字节 word Crv。2 字节 short，默认值为 4（用于曲线）。4 字节 int，默认值为 1。4 字节 点计数，4 字节 点计数，曲线的点由 2 个 short（第一个位置，第二个高度）组成。04 字节（应为 4 字节）如果为 1，则后面跟 2 字节 short，默认值为 1。4 字节 int，仅使用最后一个字节。一个通道占用一位。第一位对应 1 通道，第四位对应 4 通道，例如 256 表示已更改通道的计数，通道的有序值范围为 0~255，4 字节 word Crv。2 字节 short，默认值为 3（用于映射上的像素）。4 字节 int 通道计数 2，256 字节 short，2 表示通道索引，256 为通道的有序值，范围 0~255。"
type: docs
weight: 2660
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

CurvResource 类。曲线调整图层的资源 1 字节 - 0 表示使用曲线，1 表示在映射上使用像素；如果为 0，则：2 字节 - short，默认值为 1；4 字节 - int，仅使用最后一个字节的位。第一位对应 1 通道，第四位对应 4 通道，例如 2 字节 - short 表示点数，4 字节 * 点数 - 曲线的点，2 short：第一个位置，第二个高度；4 字节 - word "Crv "；2 字节 - short，默认值为 4（用于曲线）；4 字节 - int，默认值为 1；4 字节 - 点数，4 字节 * 点数 - 曲线的点，2 short：第一个位置，第二个高度；0-4 字节 - 用于四个通道的折叠，如果为 1，则：2 字节 - short，默认值为 1；4 字节 - int，仅使用最后一个字节。一个通道占用一位。第一位对应 1 通道，第四位对应 4 通道，例如 256 * 改变的通道数 - 按顺序的通道值，范围 0 - 255；4 字节 - word "Crv "；2 字节 - short，默认值为 3（用于映射上的像素）；4 字节 - int 通道计数 (2 + 256) 字节 - short，2 表示通道索引，256 为范围 0 - 255 的有序通道值。

```csharp
public class CurvResource : AdjustmentLayerResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | 初始化 `CurvResource` 类的新实例。 |
| [CurvResource](curvresource/#constructor_1)(int) | 初始化 `CurvResource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | 获取或设置一个值，指示此实例的数据是否以离散方式存储。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | 获取活动管理器。 |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | 获取通道数据。 |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | 获取曲线管理器。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | 类型工具信息键。 |

### 另请参阅

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


