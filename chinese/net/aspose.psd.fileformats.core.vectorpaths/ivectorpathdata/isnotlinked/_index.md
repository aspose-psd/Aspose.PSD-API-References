---
title: IVectorPathData.IsNotLinked
second_title: Aspose.PSD for .NET API 参考
description: IVectorPathData 财产. 获取或设置一个值指示此实例是否未链接
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
## IVectorPathData.IsNotLinked property

获取或设置一个值，指示此实例是否未链接。

```csharp
public bool IsNotLinked { get; set; }
```

### 适当的价值

`真的`如果此实例未链接；否则，`错误的` .

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

* interface [IVectorPathData](../)
* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* 部件 [Aspose.PSD](../../../)


