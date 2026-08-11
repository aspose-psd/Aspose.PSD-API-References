---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "ShapeLayer コンストラクタ。ShapeLayer クラスの新しいインスタンスを初期化します。すべてのリソースはデフォルト状態で作成されます"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

[`ShapeLayer`](../) クラスの新しいインスタンスを初期化します。すべてのリソースはデフォルト状態で作成されます。

```csharp
public ShapeLayer()
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


