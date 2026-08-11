---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD for .NET API Reference"
description: "DropShadowEffect プロパティ。このインスタンスが表示されているかどうかを示す値を取得または設定します"
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

このインスタンスが表示されているかどうかを示す値を取得または設定します。

```csharp
public bool IsVisible { get; set; }
```

### Property Value

このインスタンスが表示されている場合は `true`、それ以外の場合は `false`。

## 例

以下のコードは、DropShadowEffect の Opacity プロパティの使用例を示しています。

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Opacity = 20 の例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opacity = 200 の例
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 関連項目

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


