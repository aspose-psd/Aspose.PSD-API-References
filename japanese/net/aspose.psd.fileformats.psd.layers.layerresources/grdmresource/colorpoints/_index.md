---
title: "GrdmResource.ColorPoints"
second_title: "Aspose.PSD for .NET API Reference"
description: "GrdmResource プロパティ。カラーポイントを取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/
---
{{< psd/tize >}}
## GrdmResource.ColorPoints property

カラー ポイントを取得または設定します。

```csharp
public IGradientColorPoint[] ColorPoints { get; set; }
```

### Property Value

色ポイントです。

## 例

以下のコードは GrdmResource リソースのサポートを示しています。

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // 現在の値をチェック
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // 2 番目のグラデーション カラーポイントの赤色
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // 変更された値をチェック
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
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

* interface [IGradientColorPoint](../../../aspose.psd.fileformats.psd.layers/igradientcolorpoint/)
* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


