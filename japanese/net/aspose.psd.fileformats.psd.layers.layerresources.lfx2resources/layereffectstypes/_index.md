---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes 列挙. レイヤーブレンド効果.
type: docs
weight: 2660
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

レイヤーブレンド効果.

```csharp
public enum LayerEffectsTypes
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| DropShadow | `0` | ドロップ シャドウ。 |
| OuterGlow | `1` | 外側のグロー. |
| PatternOverlay | `2` | パターンオーバーレイ. |
| GradientOverlay | `3` | グラデーション オーバーレイ。 |
| ColorOverlay | `4` | カラーオーバーレイ. |
| Satin | `5` | サテン効果タイプ. |
| InnerGlow | `6` | 内側の輝き. |
| InnerShadow | `7` | 内側の影。 |
| Stroke | `8` | ストローク. |
| BevelEmboss | `9` | ベベルエンボス. |

### 例

次のコードは、ILayerEffect.EffectType プロパティのサポートを示しています。

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
            // キャッチした
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* 組み立て [Aspose.PSD](../../)


