---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD for .NET API Reference"
description: "GradientColorPoint コンストラクタ。GradientColorPoint クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

[`GradientColorPoint`](../) クラスの新しいインスタンスを初期化します。

```csharp
public GradientColorPoint()
```

### 関連項目

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

[`GradientColorPoint`](../) クラスの新しいインスタンスを初期化します。

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 色 | 色 | グラデーション上の色ポイントです。 |
| 位置 | Int32 | グラデーション上のカラーポイントの位置。 |
| medianPointLocation | Int32 | 中央値のグラデーションポイントの位置。 |

## 例

次の例は、レイヤー内で GradientOverlayEffect エフェクトオブジェクトを作成/編集する方法を示しています。

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// レイヤー内でグラデーションオーバーレイ効果を作成/取得し、編集します。
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // レイヤー内で GradientOverlayEffect を検索します。
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // 存在しない場合は新しい GradientOverlayEffect を作成できます。
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 効果に少し透明性を追加します。
    gradientOverlayEffect.Opacity = 200;

    // グラデーション効果のブレンドモードを変更します。
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // グラデーションオーバーレイ設定を構成するための GradientFillSettings オブジェクトを取得します。
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // 2 色の新しいグラデーションを設定します。
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // グラデーションの傾きを 80 度に設定します。
    settings.Angle = 80;

    // グラデーション効果を最大 150% に拡大します。
    settings.Scale = 150;

    // グラデーションのタイプを設定します。
    settings.GradientType = GradientType.Linear;

    // 各透明点で不透明度を 100% に設定して、グラデーションを不透明にします。
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


