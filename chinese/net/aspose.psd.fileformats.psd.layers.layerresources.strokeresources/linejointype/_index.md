---
title: Enum LineJoinType
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType 枚举. 线连接类型
type: docs
weight: 3050
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

线连接类型。

```csharp
public enum LineJoinType : short
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| BevelJoin | `0` | 斜面连接类型。 |
| RoundJoin | `1` | 圆形连接类型。 |
| MiterJoin | `2` | 斜接连接类型。 |

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


