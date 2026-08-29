---
title: "列挙型 LayerEffectsTypes"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes 列挙体。レイヤーブレンド効果"
type: docs
weight: 2360
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

レイヤーのブレンド効果。

```csharp
public enum LayerEffectsTypes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| DropShadow | `0` | ドロップシャドウ。 |
| OuterGlow | `1` | 外側の光。 |
| PatternOverlay | `2` | パターンオーバーレイ。 |
| GradientOverlay | `3` | グラデーションオーバーレイ。 |
| ColorOverlay | `4` | カラーオーバーレイ。 |
| Satin | `5` | サテン効果タイプ。 |
| InnerGlow | `6` | 内部グロー。 |
| InnerShadow | `7` | 内部シャドウ。 |
| Stroke | `8` | ストローク。 |
| BevelEmboss | `9` | ベベルエンボス。 |

## 例

以下のコードは ILayerEffect.EffectType プロパティのサポートを示しています。

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // 捕捉されました
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


