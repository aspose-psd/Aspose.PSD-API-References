---
title: "VibAResource.Vibrance"
second_title: "Aspose.PSD for .NET API 参考"
description: "VibAResource 属性。获取或设置鲜艳度值"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/
---
{{< psd/tize >}}
## VibAResource.Vibrance property

获取或设置鲜艳度值

```csharp
public int Vibrance { get; set; }
```

## 示例

以下代码示例演示了对 VibAResource 资源的支持。

```csharp
[C#]

// 运行时对 Vibration Resource 的读写支持示例。
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

### 另请参阅

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


