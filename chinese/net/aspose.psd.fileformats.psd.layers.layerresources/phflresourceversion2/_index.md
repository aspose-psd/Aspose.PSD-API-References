---
title: "类 PhflResourceVersion2"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 类。类 PhflResource。曝光调整图层 2 的资源，版本 3 或 2。每个 XYZ 颜色占 12/4 字节，仅在版本 3 中使用；在版本 2 中为 10 字节的颜色空间，随后是 4 个 2 字节的颜色分量。密度 4，保留亮度 1。"
type: docs
weight: 3250
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

类 PhflResource。曝光调整图层的资源，版本 2（= 3）或（= 2），每个 XYZ 颜色占 12 4 字节（仅在版本 3 中），颜色空间占 10 2 字节，随后是 4 * 2 字节的颜色分量（仅在版本 2 中），密度 4，保留亮度 1。

```csharp
public class PhflResourceVersion2 : PhflResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | 初始化 `PhflResourceVersion2` 类的新实例。 |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | 初始化 `PhflResourceVersion2` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | 获取颜色空间。 |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | 获取或设置颜色的 A 分量 |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | 获取或设置 B 分量 |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | 获取或设置颜色的 L 分量 |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 获取或设置密度。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | 获取图层资源的字节长度。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 获取或设置一个值，指示是否 [preserve luminosity]。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | 获取版本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | 获取颜色。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | 设置 RGB 颜色。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

### 另请参阅

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


