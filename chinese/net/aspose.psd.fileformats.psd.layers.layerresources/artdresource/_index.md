---
title: "类 ArtDResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ArtDResource 类。用于 GlobalLayerResources 的画板信息数据"
type: docs
weight: 2530
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/
---
{{< psd/tize >}}
## ArtDResource class

用于 [`GlobalLayerResources`](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) 的画板信息数据。

```csharp
public sealed class ArtDResource : BaseArtboardInfoResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ArtDResource](artdresource/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/) { get; set; } | 获取或设置 [`OSTypeStructure`](../ostypestructure/) 项目。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/length/) { get; } |  |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/artdresource/typetoolkey/) | 类型工具信息键。 |

## 示例

以下代码演示了对画板资源的支持。

```csharp
[C#]

string srcFile = "artboard1.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtDResource artDResource = (ArtDResource)psdImage.GlobalLayerResources[2];

    ArtBResource artBResource1 = (ArtBResource)psdImage.Layers[2].Resources[7];
    ArtBResource artBResource2 = (ArtBResource)psdImage.Layers[5].Resources[7];

    LyvrResource lyvrResource1 = (LyvrResource)psdImage.Layers[2].Resources[9];
    LyvrResource lyvrResource2 = (LyvrResource)psdImage.Layers[5].Resources[9];

    var countStruct = (IntegerStructure)artDResource.Items[0];
    AssertAreEqual(2, countStruct.Value);

    var presetNameStruct1 = (StringStructure)artBResource1.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct1.Value);

    var presetNameStruct2 = (StringStructure)artBResource2.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct2.Value);

    AssertAreEqual(160, lyvrResource1.Version);
    AssertAreEqual(160, lyvrResource2.Version);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}
```

### 另请参阅

* class [BaseArtboardInfoResource](../baseartboardinforesource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


