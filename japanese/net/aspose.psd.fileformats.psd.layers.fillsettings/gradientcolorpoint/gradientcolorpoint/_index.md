---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD for .NET API リファレンス
description: GradientColorPoint コンストラクタ. の新しいインスタンスを初期化しますGradientColorPointclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

の新しいインスタンスを初期化します[`GradientColorPoint`](../)class.

```csharp
public GradientColorPoint()
```

### 関連項目

* class [GradientColorPoint](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 組み立て [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

の新しいインスタンスを初期化します[`GradientColorPoint`](../)class.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| color | Color | グラデーション上のカラー ポイント。 |
| location | Int32 | グラデーション上のカラー ポイントの位置。 |
| medianPointLocation | Int32 | 中央グラデーション ポイントの位置。 |

### 例

次の例は、レイヤーで GradientOverlayEffect 効果オブジェクトを作成/編集する方法を示しています。

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// レイヤーのグラデーション オーバーレイ効果を作成/取得および編集します。
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // レイヤー内の GradientOverlayEffect を検索します。
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
        // 存在しない場合は、新しい GradientOverlayEffect を作成できます。
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 効果に少しの透明度を追加します。
    gradientOverlayEffect.Opacity = 200;

    // グラデーション効果のブレンド モードを変更します。
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // GradientFillSettings オブジェクトを取得して、グラデーション オーバーレイ設定を構成します。
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // 2 色の新しいグラデーションを設定します。
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // グラデーションの傾きを 80 度の角度に設定します。
    settings.Angle = 80;

    // グラデーション効果を 150% までスケールします。
    settings.Scale = 150;

    // グラデーションの種類を設定します。
    settings.GradientType = GradientType.Linear;

    // 各透過ポイントで不透明度を 100% に設定して、グラデーションを不透明にします。
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 組み立て [Aspose.PSD](../../../)


