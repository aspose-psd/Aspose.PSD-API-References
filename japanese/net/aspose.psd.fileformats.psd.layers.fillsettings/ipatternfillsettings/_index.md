---
title: Interface IPatternFillSettings
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IPatternFillSettings インターフェース. パターン塗りつぶし設定のインターフェース
type: docs
weight: 2030
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/
---
## IPatternFillSettings interface

パターン塗りつぶし設定のインターフェース

```csharp
public interface IPatternFillSettings : IFillSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/horizontaloffset/) { get; set; } | 水平オフセットを取得または設定します。 |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/linked/) { get; set; } | これが`IPatternFillSettings`リンクされています. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patterndata/) { get; set; } | パターン データを取得または設定します。 |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternheight/) { get; set; } | パターンの高さを取得または設定します。 |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternid/) { get; set; } | パターン識別子を取得または設定します。 |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternname/) { get; set; } | パターンの名前を取得または設定します。 |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternwidth/) { get; set; } | パターンの幅を取得または設定します。 |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/pointtype/) { get; set; } | ポイントのタイプを取得または設定します。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/scale/) { get; set; } | スケールを取得または設定します。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/verticaloffset/) { get; set; } | 垂直オフセットを取得または設定します。 |

### 例

次のコードは、パターン フィル レイヤーを使用して画像を保存し、Aspose.PSD がパターンをレンダリングする方法を示します。

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// 既存の画像を PsdImage クラスのインスタンスにロードします
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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 組み立て [Aspose.PSD](../../)


