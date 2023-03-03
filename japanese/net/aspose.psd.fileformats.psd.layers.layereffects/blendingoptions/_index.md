---
title: Class BlendingOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions クラス. ブレンド オプションレイヤーeffects のAPIを提供するLfx2Resourceのラッパーです
type: docs
weight: 2100
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

ブレンド オプション。レイヤーeffects のAPIを提供するLfx2Resourceのラッパーです。

```csharp
public class BlendingOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | エフェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | カラー オーバーレイを追加します。 |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | ドロップ シャドウ効果を追加します。 |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | グラデーション オーバーレイを追加します。 |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | インナー シャドウ効果を追加します。 |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | 外側のグロー効果を追加します。 |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | パターン オーバーレイを追加します。 |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | ストローク効果を追加します。 |

### 例

次のコードは、インナー シャドウ レイヤー効果の設定を変更する方法を示しています。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 組み立て [Aspose.PSD](../../)


