---
title: "列挙型 InterpolationMethod"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod 列挙型。Photoshop グラデーション補間方法のパックされた fourCC 値。ディスクリプタキー gradientsInterpolationMethod"
type: docs
weight: 2160
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Photoshop のグラデーション補間方法のためのパックされた fourCC 値です。ディスクリプタキー: \"gradientsInterpolationMethod\"

```csharp
public enum InterpolationMethod : uint
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — クラシック（キーが存在しない場合のレガシーデフォルト）。 |
| Perceptual | `1348825699` | 'Perc' — 知覚的。 |
| Linear | `1282306592` | 'Lnr ' — リニア（末尾のスペースに注意）。 |
| Smooth | `1399680879` | 'Smoo' — スムーズ。 |
| Stripes | `1195986291` | 'GIMs' — ストライプ。 |

## 例

以下のコードは、Smooth メソッドによるグラデーションレンダリングのサポートを示しています。

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // 読み取り
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // 変更
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// 保存されたデータを確認
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


