---
title: "类 LevlResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource 类。LevlResource 类。曝光调整图层的资源。"
type: docs
weight: 2950
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

类 LevlResource。曝光调整图层的资源

```csharp
public class LevlResource : AdjustmentLayerResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | 初始化 `LevlResource` 类的新实例。 |
| [LevlResource](levlresource/#constructor_1)(byte[]) | 初始化 `LevlResource` 类的新实例。支持灰度、双调、RGB、CMYK、Lab 颜色模式。2 字节 - 版本 (=2)；29 * 10 字节 - 包含 5 个短整数的级别记录集合；4 字节 - Lvls 头部（起始于索引 292）；2 字节 - 版本 (=3)；2 字节 - 总级别记录计数；10 *（总计数 - 29）；Lvls 资源的零结尾也应为四的倍数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | 获取版本。默认值为 2。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | 获取通道。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | 类型工具信息键。 |

### 另请参阅

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


