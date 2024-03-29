---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD für .NET-API-Referenz
description: GradientFillSettings eigendom. Ruft den Verlaufstyp ab oder legt ihn fest.
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Ruft den Verlaufstyp ab oder legt ihn fest.

```csharp
public GradientType GradientType { get; set; }
```

### Eigentumswert

Der Typ des Farbverlaufs.

### Beispiele

Der folgende Code speichert Bilder mit verschiedenen Farbverlaufstypen und zeigt, wie Aspose.PSD den Farbverlauf zeichnet.

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

### Siehe auch

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* Montage [Aspose.PSD](../../../)


