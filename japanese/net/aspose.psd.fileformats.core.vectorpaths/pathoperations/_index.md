---
title: "列挙型 PathOperations"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 列挙型。パス形状を組み合わせるブール演算の操作です。"
type: docs
weight: 1400
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

パス形状の結合（ブール演算）に関する操作です。

```csharp
public enum PathOperations
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 重複する形状を除外する（XOR 操作）。 |
| CombineShapes | `1` | 形状を結合する（OR 操作）。これは Photoshop のデフォルト値です。 |
| SubtractFrontShape | `2` | 前面形状を減算する（NOT 操作）。 |
| IntersectShapeAreas | `3` | 形状領域を交差させる（AND 操作）。 |

## 例

以下のコード例は、新しい LengthRecord プロパティ、PathOperations（ブール演算）、ShapeIndex および BezierKnotRecordsCount のサポートを示しています。

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // ここでは形状の組み合わせ方法を変更しています。
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


