---
title: "インターフェイス IPatternFillSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IPatternFillSettings インターフェイス。パターン塗り設定のインターフェイス"
type: docs
weight: 2150
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/
---
{{< psd/tize >}}
## IPatternFillSettings interface

パターン塗り設定のインターフェイス

```csharp
public interface IPatternFillSettings : IFillSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/angle/) { get; set; } | 取得または設定します。角度。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/horizontaloffset/) { get; set; } | 取得または設定します。水平オフセット。 |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/linked/) { get; set; } | `IPatternFillSettings` がリンクされているかどうかを示す値を取得または設定します。 |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patterndata/) { get; set; } | パターンデータを取得します。 |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternheight/) { get; set; } | 取得または設定します。パターンの高さ。 |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternid/) { get; set; } | 取得または設定します。パターン識別子。 |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternname/) { get; set; } | 取得または設定します。パターンの名前。 |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternwidth/) { get; set; } | 取得または設定します。パターンの幅。 |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/pointtype/) { get; set; } | 取得または設定します。ポイントのタイプ。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/scale/) { get; set; } | スケールを取得または設定します。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/verticaloffset/) { get; set; } | 取得または設定します。垂直オフセット。 |

## 例

以下のコードはパターン塗りつぶしレイヤーで画像を保存し、Aspose.PSD がパターンをレンダリングする方法を示します。

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (var image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var layer in image.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var settings = (IPatternFillSettings)fillLayer.FillSettings;
            settings.HorizontalOffset = -5;
            settings.VerticalOffset = 12;
            settings.Scale = 300;
            settings.Linked = true;
            settings.PatternData = new int[]
                                       {
                                           Color.Black.ToArgb(), Color.Red.ToArgb(),
                                           Color.Green.ToArgb(), Color.Blue.ToArgb(),
                                           Color.White.ToArgb(), Color.AliceBlue.ToArgb(),
                                           Color.Violet.ToArgb(), Color.Chocolate.ToArgb(),
                                           Color.IndianRed.ToArgb(), Color.DarkOliveGreen.ToArgb(),
                                           Color.CadetBlue.ToArgb(), Color.YellowGreen.ToArgb(),
                                           Color.Black.ToArgb(), Color.Azure.ToArgb(),
                                           Color.ForestGreen.ToArgb(), Color.Sienna.ToArgb(),
                                       };

            settings.PatternHeight = 4;
            settings.PatternWidth = 4;

            settings.PatternName = "$$$/Presets/Patterns/ColorfulSquare=Colorful Square New\0";
            settings.PatternId = Guid.NewGuid().ToString() + "\0";

            fillLayer.Update();
            break;
        }
    }

    image.Save(outputFile, new PsdOptions(image));
    image.Save(outputPngFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


