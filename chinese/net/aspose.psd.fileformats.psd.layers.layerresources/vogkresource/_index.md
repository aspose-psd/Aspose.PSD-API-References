---
title: Class VogkResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource 班级. Vector Origination Data 资源
type: docs
weight: 3370
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

Vector Origination Data 资源。

```csharp
public sealed class VogkResource : LayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VogkResource](vogkresource/)() | 初始化一个新的实例`VogkResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | 获取层资源所需的最小 psd 版本。 0 表示没有限制。 |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | 获取或设置形状原点设置。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | 获取图层资源签名。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | 获取或设置版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | 类型工具信息键。 |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


