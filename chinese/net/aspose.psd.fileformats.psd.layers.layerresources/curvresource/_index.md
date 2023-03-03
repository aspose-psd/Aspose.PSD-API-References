---
title: Class CurvResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource 班级. 类 CurvResource曲线调整图层资源 1 字节  如果使用曲线则为 0如果使用地图上的像素则为 1 如果为 0 则 2 字节  短默认为 1 4 字节  int仅使用最后一个字节第一位用于 1 通道第四位用于 4 通道例如 2 字节  短点 count 4 字节  点数  曲线点 2 短第一个位置第二个高度 4 字节  字Crv 2 字节  Curves 4 字节的短默认值为 4  int默认为 1 4 字节  点计数 4 字节  点计数  曲线 2 短的点第一个位置第二个高度 04 字节  导致折叠 four if 1 then 2 字节  短默认为 1 4 字节  int仅使用最后一个字节一个通道是一位第一位用于 1 个通道第四位用于 4 个通道例如 256  更改通道的计数  范围为 0  255 4 字节的通道的有序值  字Crv 2 字节  短 map 上的像素默认值为 3 4 字节  int Channel count 2  256 字节  通道索引的短 2256 是通道在 0  255 范围内的有序值
type: docs
weight: 2400
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

类 CurvResource。曲线调整图层资源 1 字节 - 如果使用曲线则为 0，如果使用地图上的像素则为 1 如果为 0 则： 2 字节 - 短。默认为 1 4 字节 - int。仅使用最后一个字节。第一位用于 1 通道，第四位用于 4 通道，例如 2 字节 - 短点 count 4 字节 * 点数 - 曲线点 2 短：第一个位置，第二个高度 4 字节 - 字“Crv” 2 字节 - Curves 4 字节的短默认值为 4 - int。默认为 1 4 字节 - 点计数 4 字节 * 点计数 - 曲线 2 短的点：第一个位置，第二个高度 0-4 字节 - 导致折叠 four if 1 then: 2 字节 - 短。默认为 1 4 字节 - int。仅使用最后一个字节。一个通道是一位。第一位用于 1 个通道，第四位用于 4 个通道，例如 256 * 更改通道的计数 - 范围为 0 - 255 4 字节的通道的有序值 - 字“Crv” 2 字节 - 短。 map 上的像素默认值为 3 4 字节 - int Channel count (2 + 256) 字节 - 通道索引的短 2，256 是通道在 0 - 255 范围内的有序值

```csharp
public class CurvResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | 初始化一个新的实例`CurvResource`类. |
| [CurvResource](curvresource/#constructor_1)(int) | 初始化一个新的实例`CurvResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | 获取或设置一个值，该值指示此实例是否为离散存储的数据。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | 获取活动管理器。 |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | 获取通道数据。 |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | 获取曲线管理器。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | 类型工具信息键。 |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


