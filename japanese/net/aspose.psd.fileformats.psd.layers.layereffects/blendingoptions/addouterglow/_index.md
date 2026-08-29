---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD for .NET API Reference"
description: "BlendingOptions メソッド。外側の光彩効果を追加します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

外側のグロー効果を追加します。

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 戻り値

作成された [`OuterGlowEffect`](../../outergloweffect/) オブジェクト

## 例

以下のコードは、OuterGlowEffect のサポートを示しています。

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### 関連項目

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


