---
title: Class DropShadowEffect
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect クラス. ドロップ シャドウ レイヤー効果
type: docs
weight: 2120
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

ドロップ シャドウ レイヤー効果

```csharp
public class DropShadowEffect : IShadowEffect
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | 度単位の角度を取得または設定します. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | 色を取得または設定します。 |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | 距離をピクセル単位で取得または設定します。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | エフェクトのタイプを取得します |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | このインスタンスが表示されるかどうかを示す値を取得または設定します. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | [ノックアウト] かどうかを示す値を取得または設定します。 |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | ノイズを取得または設定します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | 不透明度を取得または設定します。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | ピクセル単位のぼかし値を取得または設定します。 |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | 強度をパーセントで取得または設定します。 |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | [すべてのレイヤー効果でこの角度を使用する]かどうかを示す値を取得または設定します. |

### 例

次のコードは、グローバル角度値を変更するための PsdImage.GlobalAngle プロパティのサポートを示しています。

```csharp
[C#]

// DropShadowEffect.UseGlobalLight プロパティが「true」の場合、DropShadowEffect オブジェクトは PsdImage.GlobalAngle プロパティの角度値を使用します。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

次のコードは、DropShadowEffect の Opacity プロパティの使用を示しています。

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // 不透明度 = 20 の例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // 不透明度 = 20 の例0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 関連項目

* interface [IShadowEffect](../ishadoweffect/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 組み立て [Aspose.PSD](../../)


