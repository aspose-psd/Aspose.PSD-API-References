---
title: Class OuterGlowEffect
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect クラス. アウターグローレイヤー効果
type: docs
weight: 2170
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

アウターグローレイヤー効果

```csharp
public class OuterGlowEffect : ILayerEffect
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | エフェクトの種類を取得 type |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | 色を取得または設定します。 |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | 度単位の角度を取得または設定します. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | 有効なアンチエイリアシング効果を取得または設定します |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | [ノックアウト] かどうかを示す値を取得または設定します。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | このインスタンスが表示されるかどうかを示す値を取得または設定します. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | ノイズを取得または設定します。 |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | ノイズを取得または設定します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | 不透明度を取得または設定します。 |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | ノイズを取得または設定します。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | ぼかし値をピクセル単位で取得します。 |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | 強度をパーセントで取得または設定します。 |

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

* interface [ILayerEffect](../ilayereffect/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 組み立て [Aspose.PSD](../../)


