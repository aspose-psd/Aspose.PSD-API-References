---
title: "类 LayerResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResource 类。表示图层信息。"
type: docs
weight: 2480
url: /zh/net/aspose.psd.fileformats.psd.layers/layerresource/
---
{{< psd/tize >}}
## LayerResource class

表示图层信息。

```csharp
public abstract class LayerResource
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [Save](../../aspose.psd.fileformats.psd.layers/layerresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [PsbResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/psbresourcesignature/) | PSB 特定的资源签名。 |
| const [ResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/resourcesignature/) | 通用资源签名。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


