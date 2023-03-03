---
title: Enum LineCapType
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType 枚举. 线帽类型
type: docs
weight: 3040
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

线帽类型。

```csharp
public enum LineCapType : short
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| RoundCap | `0` | 圆帽类型. |
| SquareCap | `1` | 方盖类型. |
| ButtCap | `2` | 枪托盖类型. |

### 例子

下面的代码演示了对 VstkResource 资源的支持。

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* 部件 [Aspose.PSD](../../)


