---
title: Interface IVectorPathData
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData 界面. 访问矢量路径数据的接口
type: docs
weight: 1350
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

访问矢量路径数据的接口。

```csharp
public interface IVectorPathData
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | 获取或设置一个值，指示此实例是否被禁用。 |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | 获取或设置一个值，指示此实例是否反转。 |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | 获取或设置一个值，指示此实例是否未链接。 |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | 获取或设置路径记录。 |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | 获取或设置版本。 |

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

* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 部件 [Aspose.PSD](../../)


