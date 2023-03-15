---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD voor .NET API-referentie
description: GradientFillSettings eigendom. Hiermee wordt het type verloop opgehaald of ingesteld.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Hiermee wordt het type verloop opgehaald of ingesteld.

```csharp
public GradientType GradientType { get; set; }
```

### Eigendoms-waarde

Het type verloop.

### Voorbeelden

De volgende code slaat afbeeldingen op met een ander type verloop en laat zien hoe Aspose.PSD het verloop tekent.

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

### Zie ook

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* montage [Aspose.PSD](../../../)


