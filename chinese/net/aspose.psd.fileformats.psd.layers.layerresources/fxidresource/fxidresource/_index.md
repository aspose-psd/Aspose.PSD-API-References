---
title: FXidResource
second_title: Aspose.PSD for .NET API 参考
description: 初始化FXidResourceaspose.psd.fileformats.psd.layers.layerresources/fxidresource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

初始化[`FXidResource`](../../fxidresource)类.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | Int32 | 资源键。 |
| version | Int32 | 版本。 |
| filterEffectMasks | FilterEffectMaskData[] | 滤镜效果蒙版。 |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata)
* class [FXidResource](../../fxidresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->