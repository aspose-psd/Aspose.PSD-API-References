---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD för .NET API-referens
description: GradientFillSettings fast egendom. Hämtar eller ställer in typen av gradient.
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Hämtar eller ställer in typen av gradient.

```csharp
public GradientType GradientType { get; set; }
```

### Fastighetsvärde

Typen av gradient.

### Exempel

Följande kod sparar bilder med olika typer av gradient och visar hur man Aspose.PSD ritar gradienten.

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

### Se även

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* hopsättning [Aspose.PSD](../../../)


