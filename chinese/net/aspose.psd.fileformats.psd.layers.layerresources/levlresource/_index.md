---
title: Class LevlResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource 班级. 类 LevlResource曝光调整图层资源
type: docs
weight: 2640
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

类 LevlResource。曝光调整图层资源

```csharp
public class LevlResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | 初始化一个新的实例`LevlResource`类. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | 初始化一个新的实例`LevlResource` class. 支持 GrayScale、Duotone、RGB、CMYK、Lab 颜色模式 2 字节 - 版本 (=2) 29 * 10 字节 - 具有 5 个短整数的级别记录集 4 字节 - Lvls 标头（从 292 索引开始） 2 个字节 - 版本 (=3) 2 个字节 - 总级别记录的计数 10 *（总计数 - 29） Lvls 资源的零结尾也应该折叠为四个 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | 获取版本。默认为 2 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | 获取频道。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | 类型工具信息键。 |

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


