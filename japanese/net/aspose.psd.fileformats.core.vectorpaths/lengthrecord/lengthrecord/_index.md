---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD for .NET API Reference"
description: "LengthRecord コンストラクタ。LengthRecord クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

[`LengthRecord`](../) クラスの新しいインスタンスを初期化します。

```csharp
public LengthRecord(byte[] data)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | Byte[] | レコードデータです。 |

### 関連項目

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

[`LengthRecord`](../) クラスの新しいインスタンスを初期化します。

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


