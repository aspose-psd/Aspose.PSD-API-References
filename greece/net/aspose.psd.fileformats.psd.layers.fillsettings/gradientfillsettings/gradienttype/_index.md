---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD για Αναφορά API .NET
description: GradientFillSettings ιδιοκτησία. Λαμβάνει ή ορίζει τον τύπο της κλίσης.
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Λαμβάνει ή ορίζει τον τύπο της κλίσης.

```csharp
public GradientType GradientType { get; set; }
```

### Αξία περιουσίας

Ο τύπος της κλίσης.

### Παραδείγματα

Ο παρακάτω κώδικας αποθηκεύει εικόνες με διαφορετικό τύπο διαβάθμισης και δείχνει πώς να Aspose.Το PSD σχεδιάζει τη διαβάθμιση.

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

### Δείτε επίσης

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* συνέλευση [Aspose.PSD](../../../)


