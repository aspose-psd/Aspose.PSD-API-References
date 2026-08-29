---
title: "IVectorPathData.Version"
second_title: "Aspose.PSD for .NET API Reference"
description: "IVectorPathData プロパティ。 バージョンを取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/
---
{{< psd/tize >}}
## IVectorPathData.Version property

バージョンを取得または設定します。

```csharp
public int Version { get; set; }
```

### Property Value

バージョンです。

## 例

この例は、Crop 操作の正しい動作のために PsdImage.ImageResources で 'WorkingPathResource' リソースのサポートを示しています。

```csharp
[C#]

// 画像を切り取り、保存します。
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource リソースを検索します。
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

    // 切り取り、保存します。
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// 保存された画像を読み込み、変更を確認します。
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource リソースを検索します。
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

### 関連項目

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


