---
title: "インターフェイス IVectorPathData"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData インターフェイス。ベクトルパスデータへのアクセス用インターフェイスです。"
type: docs
weight: 1360
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

ベクトルパスデータへのアクセス用インターフェイスです。

```csharp
public interface IVectorPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | パス レコードを取得または設定します。 |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | バージョンを取得または設定します。 |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


