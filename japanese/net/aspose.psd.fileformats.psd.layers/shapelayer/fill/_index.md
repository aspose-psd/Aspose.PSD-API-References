---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD for .NET API Reference"
description: "ShapeLayer プロパティ。Shape レイヤー内のシェイプの内部領域の塗り設定を取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

シェイプレイヤー内のシェイプの内部領域の塗り設定を取得または設定します。

```csharp
public IFillSettings Fill { get; set; }
```

## 例

次のコードは ShapeLayer の Fill プロパティを示しています。

```csharp
[C#]

string srcFile = "ShapeInternalSolid.psd";
string outFile = "ShapeInternalSolid.psd.out.psd";

using (PsdImage image = (PsdImage)Image.Load(
           srcFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.Red;

    shapeLayer.Update();

    image.Save(outFile);
}

// 保存された変更を確認する
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;

    AssertAreEqual(Color.Red, fillSettings.Color);

    image.Save(outFile);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 関連項目

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


