---
title: IVectorPathData.IsDisabled
second_title: Aspose.PSD for .NET API リファレンス
description: IVectorPathData 財産. このインスタンスが無効かどうかを示す値を取得または設定します
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
## IVectorPathData.IsDisabled property

このインスタンスが無効かどうかを示す値を取得または設定します。

```csharp
public bool IsDisabled { get; set; }
```

### プロパティ値

`真実`このインスタンスが無効になっている場合。さもないと、`間違い` .

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

* interface [IVectorPathData](../)
* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* 組み立て [Aspose.PSD](../../../)


