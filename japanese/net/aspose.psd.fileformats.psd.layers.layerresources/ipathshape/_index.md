---
title: "インターフェイス IPathShape"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPathShape インターフェイス。ベジェ曲線のノットからなるシェイプ"
type: docs
weight: 2810
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---
{{< psd/tize >}}
## IPathShape interface

ベジェ曲線のノットからなるシェイプです。

```csharp
public interface IPathShape
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/isclosed/) { get; set; } | シェイプが閉じているかどうかを決定するプロパティを取得または設定します。 |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/pathoperations/) { get; set; } | パス形状の結合（ブール演算）に関する操作です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/getitems/)() | ベジェノットの配列を取得します。 |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/setitems/)(BezierKnotRecord[]) | Bexier ノットの配列を割り当てます。 |

## 例

次のコードは ShapeLayer 用の vsms または vmsk リソースからのパスオブジェクトを示しています。

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // シェイプを1つ削除する
    shapes.RemoveAt(1);

    // 変更されたデータをリソースに保存する
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// 保存されたファイルの変更値を確認する
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // 保存されたファイルにはシェイプが1つ含まれているはずです
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
                lengthRecord = null;
                bezierKnotRecords.Clear();
            }

            lengthRecord = (LengthRecord)pathRecord;
        }
        else if (pathRecord is BezierKnotRecord)
        {
            bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
        }
        else if (pathRecord is InitialFillRuleRecord)
        {
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


