---
title: "IVectorPathData.IsInverted"
second_title: "Aspose.PSD for .NET API 参考"
description: "IVectorPathData 属性。获取或设置一个值，指示此实例是否已反转"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
{{< psd/tize >}}
## IVectorPathData.IsInverted property

获取或设置一个值，以指示此实例是否已反转。

```csharp
public bool IsInverted { get; set; }
```

### Property Value

`true` 表示此实例已反转；否则为 `false`。

## 示例

此示例演示在 PsdImage.ImageResources 中对 'WorkingPathResource' 资源的支持，以正确执行裁剪操作。

```csharp
[C#]

// 裁剪图像并保存。
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

    // 裁剪并保存。
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// 加载已保存的图像并检查更改。
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

### 另请参阅

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


