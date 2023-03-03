---
title: Class VectorShapeOriginSettings
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings 班级. 矢量形状起源设置
type: docs
weight: 1440
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

矢量形状起源设置。

```csharp
public sealed class VectorShapeOriginSettings
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | 初始化一个新的实例`VectorShapeOriginSettings`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | 获取一个值，指示此实例是否具有原点框角属性。 |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | 获取一个值，指示此实例是否具有原始索引属性。 |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | 获取一个值，该值指示此实例是否具有原点半径矩形属性。 |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | 获取一个值，该值指示此实例是否具有原始分辨率属性。 |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | 获取一个值，该值指示此实例是否具有矩形属性。 |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | 获取一个值，指示此实例是否具有原始类型属性。 |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | 获取或设置一个值，指示形状是否无效。 |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | 获取一个值，该值指示此实例是否具有形状无效属性集。 |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | 获取一个值，指示此实例是否具有转换属性。 |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | 获取或设置原点框角。 |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | 获取或设置原点形状索引。 |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | 获取或设置原点半径矩形。 |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | 获取或设置原点分辨率。 |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | 获取或设置原点形状边界框。 |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | 获取或设置原点的类型。 |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | 获取或设置转换矩阵。 |

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

* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 部件 [Aspose.PSD](../../)


