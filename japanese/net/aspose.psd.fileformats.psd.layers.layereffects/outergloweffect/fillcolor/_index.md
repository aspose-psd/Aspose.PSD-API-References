---
title: OuterGlowEffect.FillColor
second_title: Aspose.PSD for .NET API リファレンス
description: OuterGlowEffect 財産. 色を取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
## OuterGlowEffect.FillColor property

色を取得または設定します。

```csharp
public IFillSettings FillColor { get; set; }
```

### プロパティ値

色.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* 組み立て [Aspose.PSD](../../../)


