---
title: Class InnerShadowEffect
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect クラス. インナー シャドウ レイヤー effect
type: docs
weight: 2160
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

インナー シャドウ レイヤー effect

```csharp
public class InnerShadowEffect : IShadowEffect
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | 度単位の角度を取得または設定します. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | 色を取得または設定します。 |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | 距離をピクセル単位で取得または設定します。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | エフェクトのタイプを取得します |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | このインスタンスが表示されるかどうかを示す値を取得または設定します. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | ノイズを取得または設定します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | 不透明度を取得または設定します。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | ピクセル単位のぼかし値を取得または設定します。 |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | スプレッド (チョーク) をパーセンテージで取得または設定します。 |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | [すべてのレイヤー効果でこの角度を使用する]かどうかを示す値を取得または設定します. |

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

* interface [IShadowEffect](../ishadoweffect/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 組み立て [Aspose.PSD](../../)


