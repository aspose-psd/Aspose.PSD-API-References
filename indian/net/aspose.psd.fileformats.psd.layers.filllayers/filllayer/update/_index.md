---
title: "FillLayer.Update"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FillLayer मेथड। वर्तमान IFillSettings के आधार पर फ़िल लेयर के पिक्सेल डेटा को अपडेट करता है।"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
{{< psd/tize >}}
## FillLayer.Update method

वर्तमान [`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) के आधार पर फ़िल लेयर के पिक्सेल डेटा को अपडेट करता है।

```csharp
public void Update()
```

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | जब कोई अज्ञात FillType मिलता है तो थ्रो किया जाता है। |

## उदाहरण

निम्नलिखित कोड Fill लेयर्स के समर्थन को दर्शाता है: Color fill।

```csharp
[C#]

// Fill लेयर्स का समर्थन जोड़ें: Color fill
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

निम्नलिखित कोड विभिन्न प्रकार के ग्रेडिएंट के साथ छवियों को सहेजता है और दिखाता है कि Aspose.PSD ग्रेडिएंट को कैसे ड्रॉ करता है।

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

निम्नलिखित कोड पैटर्न फ़िल लेयर के साथ छवियों को सहेजता है और दिखाता है कि Aspose.PSD पैटर्न को कैसे रेंडर करता है।

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
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

### देखें भी

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


