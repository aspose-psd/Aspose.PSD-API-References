---
title: VogkResource.PsdVersion
second_title: Aspose.PSD for .NET API 参考
description: VogkResource 财产. 获取层资源所需的最小 psd 版本 0 表示没有限制
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/
---
## VogkResource.PsdVersion property

获取层资源所需的最小 psd 版本。 0 表示没有限制。

```csharp
public override int PsdVersion { get; }
```

### 例子

以下示例演示了 VogkResource 资源的支持。

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // 阅读
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // 编辑
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### 也可以看看

* class [VogkResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* 部件 [Aspose.PSD](../../../)


