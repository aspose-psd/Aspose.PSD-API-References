---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD for .NET API リファレンス
description: WorkingPathResource コンストラクタ. の新しいインスタンスを初期化しますWorkingPathResourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

の新しいインスタンスを初期化します[`WorkingPathResource`](../)class.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| dataBytes | Byte[] | ベクターパスのデータ。 |

### 例

この例では、Crop 操作を正しく機能させるために、PsdImage.ImageResources 内の「WorkingPathResource」リソースのサポートを示しています。

```csharp
[C#]

// 画像をトリミングして保存します。
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

    // トリミングして保存します。
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// 保存した画像を読み込み、変更を確認します。
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

* class [WorkingPathResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* 組み立て [Aspose.PSD](../../../)


