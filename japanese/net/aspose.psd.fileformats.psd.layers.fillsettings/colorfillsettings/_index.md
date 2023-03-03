---
title: Class ColorFillSettings
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.ColorFillSettings クラス. 塗りつぶし効果の設定
type: docs
weight: 1930
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---
## ColorFillSettings class

塗りつぶし効果の設定

```csharp
public class ColorFillSettings : BaseFillSettings, IColorFillSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/color/) { get; set; } | 色を取得または設定します。 |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/filltype/) { get; } | 塗りつぶしタイプ |

### 例

次のコードは、塗りつぶしタイプ - カラーを使用したストローク エフェクト レイヤーのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

var sourceFileName = "Stroke.psd";
var exportPath = "StrokeColorChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, colorStroke.BlendMode);
    AssertAreEqual((byte)255, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);

    fillSettings.Color = Color.Yellow;

    colorStroke.Opacity = 127;
    colorStroke.BlendMode = BlendMode.Color;
    im.Save(exportPath);
}

// 編集後のテストファイル
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, colorStroke.BlendMode);
    AssertAreEqual((byte)127, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Yellow, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);
}
```

### 関連項目

* class [BaseFillSettings](../basefillsettings/)
* interface [IColorFillSettings](../icolorfillsettings/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 組み立て [Aspose.PSD](../../)


