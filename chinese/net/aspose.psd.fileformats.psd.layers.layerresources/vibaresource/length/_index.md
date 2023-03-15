---
title: VibAResource.Length
second_title: Aspose.PSD for .NET API 参考
description: VibAResource 财产. 获取以字节为单位的层资源长度
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
## VibAResource.Length property

获取以字节为单位的层资源长度。

```csharp
public override int Length { get; }
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


