---
title: "OuterGlowEffect.Intensity"
second_title: "Aspose.PSD for .NET API Reference"
description: "OuterGlowEffect プロパティ。角度（度）を取得または設定します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

角度（度）を取得または設定します。

```csharp
public int Intensity { get; set; }
```

### Property Value

角度です。

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


