---
title: "クラス BlendingOptions"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions クラス。BlendingOptions。これは BaseFxResource のラッパーで、レイヤー効果の API を提供します。"
type: docs
weight: 2290
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions。これは BaseFxResource のラッパーで、レイヤー効果の API を提供します。

```csharp
public class BlendingOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | すべてのレイヤー効果の可視性を取得または設定します。 |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | エフェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | カラーオーバーレイを追加します。 |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | ドロップシャドウ効果を追加します。 |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | グラデーションオーバーレイを追加します。 |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | インナーレイヤーシャドウ効果を追加します。 |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | 外側のグロー効果を追加します。 |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | パターンオーバーレイを追加します。 |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | ストローク効果を追加します。 |

## 例

以下のコードは、インナーレイヤーシャドウ効果の設定を変更する方法を示しています。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


