---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD for .NET API 参考
description: WorkingPathResource 构造函数. 初始化一个新的实例WorkingPathResource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

初始化一个新的实例[`WorkingPathResource`](../)类.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| dataBytes | Byte[] | 矢量路径的数据。 |

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

* class [WorkingPathResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* 部件 [Aspose.PSD](../../../)


