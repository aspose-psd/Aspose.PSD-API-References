---
title: VibAResource.VibAResource
second_title: Aspose.PSD for .NET API 参考
description: VibAResource 构造函数. 初始化一个新的实例VibAResource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
## VibAResource constructor

初始化一个新的实例[`VibAResource`](../)类.

```csharp
public VibAResource()
```

### 例子

以下代码示例演示了对 VibAResource 资源的支持。

```csharp
[C#]

// 运行时支持读写振动资源的例子。
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 也可以看看

* class [VibAResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* 部件 [Aspose.PSD](../../../)


