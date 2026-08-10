---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα IGradientFillSettings. Λαμβάνει ή ορίζει τον τύπο της διαβάθμισης"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό.

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

Ο τύπος της διαβάθμισης.

## Παραδείγματα

Ο παρακάτω κώδικας αποθηκεύει εικόνες με διαφορετικούς τύπους διαβάθμισης και δείχνει πώς το Aspose.PSD σχεδιάζει τη διαβάθμιση.

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
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


