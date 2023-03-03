---
title: OuterGlowEffect.Jitter
second_title: Aspose.PSD for .NET API リファレンス
description: OuterGlowEffect 財産. ノイズを取得または設定します
type: docs
weight: 80
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
## OuterGlowEffect.Jitter property

ノイズを取得または設定します。

```csharp
public int Jitter { get; set; }
```

### プロパティ値

ノイズ.

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | ノイズは、0 から 100 の範囲のパーセンテージで指定する必要があります |

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


