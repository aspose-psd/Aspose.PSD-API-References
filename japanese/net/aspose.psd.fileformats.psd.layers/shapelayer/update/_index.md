---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD for .NET API Reference"
description: "ShapeLayer メソッド。Shape レイヤーのプロパティからリソースを更新します"
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

シェイプレイヤーのプロパティからリソースを更新します。

```csharp
public void Update()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


