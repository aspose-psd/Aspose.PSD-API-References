---
title: Class NvrtResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource 班级. 类 NvrtResource反转调整图层资源.
type: docs
weight: 2840
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

类 NvrtResource。反转调整图层资源.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | 初始化一个新的实例`NvrtResource`类. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | 初始化一个新的实例`NvrtResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | 获取 PSD 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 获取签名. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | 类型工具信息键。 |

### 例子

以下示例演示如何获取 NvrtResource。

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // 支持 NvrtResource。
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


