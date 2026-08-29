---
title: "OuterGlowEffect.Size"
second_title: "Aspose.PSD for .NET API Reference"
description: "OuterGlowEffect プロパティ。ピクセル単位のぼかし値を取得します"
type: docs
weight: 120
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
{{< psd/tize >}}
## OuterGlowEffect.Size property

ぼかし値（ピクセル単位）を取得します。

```csharp
public int Size { get; set; }
```

### Property Value

サイズです。

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


