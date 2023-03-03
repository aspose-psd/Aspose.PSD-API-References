---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD for .NET API リファレンス
description: OuterGlowEffect 財産. 度単位の角度を取得または設定します.
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

度単位の角度を取得または設定します.

```csharp
public int Intensity { get; set; }
```

### プロパティ値

角度.

### 例

次のコードは、OuterGlowEffect のサポートを示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* 組み立て [Aspose.PSD](../../../)


