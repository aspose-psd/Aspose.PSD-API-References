---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD for .NET API Reference"
description: "ShapeLayer プロパティ。Shape レイヤーに存在するパスの集合を取得します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

シェイプレイヤーに存在するパスの集合を取得します。

```csharp
public IPath Path { get; }
```

## 例

以下のコードは ShapeLayer レイヤーのサポートを示しています。

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // ソースファイルには 2 つの図形が含まれています。2 番目の図形を削除します。
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### 関連項目

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


