---
title: "OuterGlowEffect.Range"
second_title: "Aspose.PSD for .NET API Reference"
description: "OuterGlowEffect プロパティ。ノイズを取得または設定します"
type: docs
weight: 110
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
{{< psd/tize >}}
## OuterGlowEffect.Range property

ノイズを取得または設定します。

```csharp
public int Range { get; set; }
```

### Property Value

ノイズです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | ノイズは 0 から 100 の範囲のパーセンテージで指定する必要があります |

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


