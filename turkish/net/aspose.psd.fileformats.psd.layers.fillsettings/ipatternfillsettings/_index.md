---
title: "Arayüz IPatternFillSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IPatternFillSettings arayüz. Desen doldurma ayarları için arayüz"
type: docs
weight: 2150
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/
---
{{< psd/tize >}}
## IPatternFillSettings interface

Desen doldurma ayarları için arayüz

```csharp
public interface IPatternFillSettings : IFillSettings
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/angle/) { get; set; } | Açıyı alır veya ayarlar. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/horizontaloffset/) { get; set; } | Yatay ofseti alır veya ayarlar. |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/linked/) { get; set; } | Bu `IPatternFillSettings`'in bağlanıp bağlanmadığını gösteren bir değeri alır veya ayarlar. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patterndata/) { get; set; } | Desen verilerini alır. |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternheight/) { get; set; } | Desenin yüksekliğini alır veya ayarlar. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternid/) { get; set; } | Desen tanımlayıcısını alır veya ayarlar. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternname/) { get; set; } | Desenin adını alır veya ayarlar. |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternwidth/) { get; set; } | Desenin genişliğini alır veya ayarlar. |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/pointtype/) { get; set; } | Noktanın tipini alır veya ayarlar. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/scale/) { get; set; } | Ölçeği alır veya ayarlar. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/verticaloffset/) { get; set; } | Dikey ofseti alır veya ayarlar. |

## Örnekler

Aşağıdaki kod, desen Doldurma Katmanı ile görüntüleri kaydeder ve Aspose.PSD'nin deseni nasıl işlediğini gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
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

### Ayrıca Bakınız

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


