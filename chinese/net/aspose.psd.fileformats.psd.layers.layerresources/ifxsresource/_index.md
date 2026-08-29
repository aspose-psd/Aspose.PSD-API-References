---
title: "类 IfxsResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource 类。Ifxs 资源组图层效果资源"
type: docs
weight: 2840
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs 资源（组图层效果资源）

```csharp
public sealed class IfxsResource : BaseFxResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [IfxsResource](ifxsresource/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | 获取描述符版本。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | 类型工具信息键。 |

## 示例

以下代码演示了 IfxsResource 的支持。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // 示例包含 2 个带效果的组图层
    // 带单个效果的组图层
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // 带多个效果的组图层
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // 获取效果数量并验证其数量
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // 组图层中的一个效果位于资源 'IfxsResource' 中
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // 组图层中的两个或更多效果位于资源 'ImfxResource' 中
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // 为具有多重效果的组图层添加第三个阴影
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### 另请参阅

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


