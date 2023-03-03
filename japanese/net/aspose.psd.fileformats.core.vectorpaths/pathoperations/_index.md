---
title: Enum PathOperations
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 列挙. パス シェイプを結合する操作 ブール演算.
type: docs
weight: 1390
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

パス シェイプを結合する操作 (ブール演算).

```csharp
public enum PathOperations
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 重なり合う形状を除外 (XOR 演算). |
| CombineShapes | `1` | 図形を結合します (OR 演算)。これは Photoshop のデフォルト値です。 |
| SubtractFrontShape | `2` | 前面形状を減算します (演算ではありません). |
| IntersectShapeAreas | `3` | 交差形状領域 (AND 演算). |

### 例

次のコード例は、新しい LengthRecord プロパティ、PathOperations (ブール演算)、ShapeIndex、および BezierKnotRecordsCount のサポートを示しています。

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

    // ここで、シェイプ間の結合方法を変更します。
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 組み立て [Aspose.PSD](../../)


