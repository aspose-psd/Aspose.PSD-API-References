---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD for .NET API リファレンス
description: BlendingOptions 方法. 外側のグロー効果を追加します
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

外側のグロー効果を追加します。

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 戻り値

作成済み[`OuterGlowEffect`](../../outergloweffect/)object

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* 組み立て [Aspose.PSD](../../../)


