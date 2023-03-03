---
title: Class WorkingPathResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource 班级. 工作路径资源.
type: docs
weight: 3980
url: /zh/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

工作路径资源.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | 初始化一个新的实例`WorkingPathResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | 获取以字节为单位的资源数据大小。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | 获取或设置一个值，指示此实例是否被禁用。 |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | 获取或设置一个值，指示此实例是否反转。 |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | 获取或设置一个值，指示此实例是否未链接。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。 Pascal 字符串，填充以使大小均匀（空名称由两个字节 0 组成）. |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | 获取或设置路径记录。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为“8BIM”. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 获取以字节为单位的资源块大小，包括其数据。 |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | 获取或设置版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 验证资源值。 |

### 例子

此示例演示了 PsdImage.ImageResources 中“WorkingPathResource”资源的支持，以便正确处理 Crop 操作。

```csharp
[C#]

//裁剪图像并保存。
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // 搜索 WorkingPathResource 资源。
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    //裁剪并保存。
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// 加载保存的图像并检查更改。
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // 搜索 WorkingPathResource 资源。
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### 也可以看看

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 部件 [Aspose.PSD](../../)


