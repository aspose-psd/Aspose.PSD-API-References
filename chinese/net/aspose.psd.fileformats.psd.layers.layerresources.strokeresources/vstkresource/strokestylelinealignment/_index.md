---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD for .NET API 参考
description: VstkResource 财产. 获取或设置 Stroke 样式线条对齐方式
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

获取或设置 Stroke 样式线条对齐方式。

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* 部件 [Aspose.PSD](../../../)


