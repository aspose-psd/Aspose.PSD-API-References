---
title: FillLayer.Update
second_title: Aspose.PSD for .NET API リファレンス
description: FillLayer 方法. 実際に従って塗りつぶしレイヤー ピクセル データを更新しますIFillSettings .
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
## FillLayer.Update method

実際に従って塗りつぶしレイヤー ピクセル データを更新します。[`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) .

```csharp
public void Update()
```

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | FillType のタイプが不明です |

### 例

次のコードは、塗りつぶしレイヤーのサポートを示しています。

```csharp
[C#]

// 塗りつぶしレイヤーのサポートを追加: カラー塗りつぶし
string sourceFileName = "ColorFillLayer.psd";
string exportPath = "ColorFillLayer_output.psd";

var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Color)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IColorFillSettings)fillLayer.FillSettings;
            settings.Color = Color.Red;
            fillLayer.Update();
            im.Save(exportPath);
            break;
        }
    }
}
```

次のコードは、さまざまなタイプのグラデーションで画像を保存し、Aspose.PSD がグラデーションを描画する方法を示しています。

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

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

* class [FillLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 組み立て [Aspose.PSD](../../../)


