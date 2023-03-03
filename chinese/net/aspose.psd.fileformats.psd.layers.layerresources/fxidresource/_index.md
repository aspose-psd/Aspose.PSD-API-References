---
title: Class FXidResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource 班级. 滤镜效果资源包含通道用户蒙版和智能滤镜的工作表蒙版
type: docs
weight: 2460
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
## FXidResource class

滤镜效果资源包含通道、用户蒙版和智能滤镜的工作表蒙版。

```csharp
public sealed class FXidResource : LayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | 初始化一个新的实例`FXidResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | 获取滤镜效果遮罩。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/psdversion/) { get; } | 获取层资源所需的最小 psd 版本。 0 表示没有限制。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/signature/) { get; } | 获取图层资源签名。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | 获取版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | 类型工具信息密钥 FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | 类型工具信息密钥 FXid. |

### 例子

此示例演示如何获取和设置 FXidResource 资源的属性。

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// 保存后检查
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### 也可以看看

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


