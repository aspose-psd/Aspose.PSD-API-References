---
title: "IGradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD for .NET API Reference"
description: "IGradientFillSettings プロパティ。グラデーションの補間方法を取得または設定します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## IGradientFillSettings.InterpolationMethod property

グラデーションの補間方法を取得または設定します。

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

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

* enum [InterpolationMethod](../../interpolationmethod/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


