---
title: "LengthRecord.PathOperations"
second_title: "Aspose.PSD for .NET API Reference"
description: "LengthRecord プロパティ。パス操作を取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
{{< psd/tize >}}
## LengthRecord.PathOperations property

パス操作を取得または設定します。

```csharp
public PathOperations PathOperations { get; set; }
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

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


