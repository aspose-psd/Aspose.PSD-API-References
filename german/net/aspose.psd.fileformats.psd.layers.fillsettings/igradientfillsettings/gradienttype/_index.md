---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IGradientFillSettings property. Gibt den Typ des Verlaufs zurück oder legt ihn fest"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

Liest oder setzt den Typ des Verlaufs.

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

Der Typ des Farbverlaufs.

## Beispiele

Der folgende Code speichert Bilder mit unterschiedlichen Verlaufsarten und zeigt, wie Aspose.PSD den Verlauf zeichnet.

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
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


