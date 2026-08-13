---
title: "FillLayer.Update"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FillLayer yöntemi. Doldurma katmanının piksel verilerini mevcut IFillSettings temelinde günceller"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
{{< psd/tize >}}
## FillLayer.Update method

Doldurma katmanının piksel verilerini mevcut [`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) temelinde günceller.

```csharp
public void Update()
```

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Bilinmeyen bir FillType ile karşılaşıldığında fırlatılır. |

## Örnekler

Aşağıdaki kod, Fill katmanlarının desteğini gösterir: Renk doldurma.

```csharp
[C#]

// Fill katmanlarının desteğini ekle: Renk doldurma
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

Aşağıdaki kod, farklı degrade tipleriyle görüntüler kaydeder ve Aspose.PSD'nin degradeyi nasıl çizdiğini gösterir.

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

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


