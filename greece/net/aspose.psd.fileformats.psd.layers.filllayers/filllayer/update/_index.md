---
title: FillLayer.Update
second_title: Aspose.PSD για Αναφορά API .NET
description: FillLayer μέθοδος. Ενημερώνει τα δεδομένα εικονοστοιχείων γεμίσματος επιπέδου σύμφωνα με τα πραγματικάIFillSettings .
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
## FillLayer.Update method

Ενημερώνει τα δεδομένα εικονοστοιχείων γεμίσματος επιπέδου σύμφωνα με τα πραγματικά[`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) .

```csharp
public void Update()
```

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Άγνωστος τύπος FillType |

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη των επιπέδων γεμίσματος: Έγχρωμο γέμισμα.

```csharp
[C#]

// Προσθήκη υποστήριξης επιπέδων γεμίσματος: Έγχρωμο γέμισμα
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

Ο παρακάτω κώδικας αποθηκεύει εικόνες με μοτίβο Fill Layer και δείχνει πώς το Aspose.PSD αποδίδει το μοτίβο.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
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

### Δείτε επίσης

* class [FillLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* συνέλευση [Aspose.PSD](../../../)


