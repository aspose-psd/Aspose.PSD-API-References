---
title: "Κλάση GradientFillSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings κλάση. Βασική κλάση ορισμού διαβάθμισης. Περιέχει κοινές ιδιότητες για και τους δύο τύπους διαβάθμισης Στερεά και Θόρυβο."
type: docs
weight: 2070
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
{{< psd/tize >}}
## GradientFillSettings class

Βασική κλάση ορισμού διαβάθμισης. Περιέχει κοινές ιδιότητες για και τους δύο τύπους διαβάθμισης (Σταθερή και Θόρυβος).

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `BaseGradientFillSettings` είναι με θόρυβο. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `GradientFillSettings` είναι δεντρά. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | Λαμβάνει τη λειτουργία για αυτή τη διαβάθμιση. Καθορίζει 'Τύπος Διαβάθμισης' = 'Στερεό/Θόρυβο' (0/1). |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradient/) { get; set; } | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `BaseGradientFillSettings` είναι αντίστροφο. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/interpolationmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `GradientFillSettings` είναι αντίστροφο. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | Λαμβάνει ή ορίζει την **κανονικοποιημένη** κλίμακα διαβάθμισης (σε ποσοστό) |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | Απαρίθμηση GradientType |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του επιπέδου εφέ γραμμής με τύπο γεμίσματος - Gradient.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Σημεία Χρώματος
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    var colorPoints = solidGradient.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Σημεία Διαφάνειας
    var transparencyPoints = solidGradient.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Δοκιμή επεξεργασίας
    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // Προσθήκη νέου σημείου χρώματος
    var colorPoint = solidGradient.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Αλλαγή θέσης του προηγούμενου σημείου
    solidGradient.ColorPoints[1].Location = 1899;

    // Προσθήκη νέου σημείου διαφάνειας
    var transparencyPoint = solidGradient.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Αλλαγή θέσης του προηγούμενου σημείου διαφάνειας
    solidGradient.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Αρχείο δοκιμής μετά την επεξεργασία
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Έλεγχος σημείων χρώματος
    AssertAreEqual(3, solidGradient.ColorPoints.Length);

    var point = solidGradient.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = solidGradient.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = solidGradient.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Έλεγχος διαφανών σημείων
    AssertAreEqual(3, solidGradient.TransparencyPoints.Length);

    var transparencyPoint = solidGradient.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Δείτε επίσης

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


