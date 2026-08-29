---
title: "クラス NoiseGradient"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.NoiseGradient クラス。ノイズグラデーション定義クラスです"
type: docs
weight: 2220
url: /ja/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/
---
{{< psd/tize >}}
## NoiseGradient class

ノイズグラデーション定義クラスです。

```csharp
public class NoiseGradient : BaseGradient
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [NoiseGradient](noisegradient/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/colormodel/) { get; set; } | カラー モデル - RGB/HSB/LAB（3/4/6）を取得または設定します。 |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/) { get; set; } | 拡張カウント（= Photoshop 6.0 の場合は 2）を取得または設定します。 |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/gradientmode/) { get; } | このグラデーションのモードを取得します。'Gradient Type' = 'Solid/Noise' (0/1) を決定します。 |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | グラデーションの名前を取得または設定します。 |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/maximumcolor/) { get; set; } | PixelDataFormat の最大色を取得または設定します。 |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/minimumcolor/) { get; set; } | PixelDataFormat の最小色を取得または設定します。 |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/rndnumberseed/) { get; set; } | ノイズグラデーションの色生成に使用される乱数シードを取得または設定します。 |
| [Roughness](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/roughness/) { get; set; } | 粗さ係数を取得または設定します。 |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/showtransparency/) { get; set; } | 透過表示のフラグを取得または設定します。 |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/usevectorcolor/) { get; set; } | ベクトルカラー使用のフラグを取得または設定します。 |

## 例

ストローク塗り効果におけるノイズとソリッドのグラデーション設定の読み取りと変更を示します。

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // 共通のグラデーション塗り設定プロパティを確認
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // ノイズグラデーションのプロパティを確認
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // グラデーション設定を変更する
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// 保存された変更を確認する
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // 共通のグラデーション塗り設定プロパティを確認
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### 関連項目

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


