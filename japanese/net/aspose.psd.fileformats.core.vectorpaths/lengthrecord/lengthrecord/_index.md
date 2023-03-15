---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD for .NET API リファレンス
description: LengthRecord コンストラクタ. の新しいインスタンスを初期化しますLengthRecordclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

の新しいインスタンスを初期化します[`LengthRecord`](../)class.

```csharp
public LengthRecord(byte[] data)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| data | Byte[] | 記録データです。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| !:PsdImageArgumentException | LengthRecord 作成のための不正なデータ |

### 関連項目

* class [LengthRecord](../)
* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* 組み立て [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

の新しいインスタンスを初期化します[`LengthRecord`](../)class.

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* 組み立て [Aspose.PSD](../../../)


