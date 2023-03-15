---
title: Class GradientFillSettings
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings τάξη. Ρυθμίσεις εφέ πλήρωσης κλίσης.
type: docs
weight: 1960
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
## GradientFillSettings class

Ρυθμίσεις εφέ πλήρωσης κλίσης.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | Αρχικοποιεί μια νέα παρουσία του`GradientFillSettings` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [ευθυγράμμιση με το επίπεδο]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | Παίρνει ή ρυθμίζει τη γωνία. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/color/) { get; set; } | Παίρνει ή ρυθμίζει το χρώμα. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/colorpoints/) { get; set; } | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό`GradientFillSettings` είναι διχασμός. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | Ο τύπος πλήρωσης |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradientname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα της διαβάθμισης. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο της κλίσης. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό`GradientFillSettings` είναι αντίστροφη. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | Παίρνει ή ρυθμίζει την κλίμακα. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/transparencypoints/) { get; set; } | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addcolorpoint/)() | Προσθέτει το σημείο χρώματος. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addtransparencypoint/)() | Προσθέτει το σημείο χρώματος. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removecolorpoint/)(IGradientColorPoint) | Αφαιρεί το σημείο χρώματος. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removetransparencypoint/)(IGradientTransparencyPoint) | Αφαιρεί το σημείο διαφάνειας. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/generatelfx2resourcenodes/)() | Δημιουργεί τους κόμβους πόρων LFX2. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του επιπέδου εφέ stroke με τύπο γεμίσματος - Gradient.

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
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Σημεία χρώματος
    var colorPoints = fillSettings.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Σημεία διαφάνειας
    var transparencyPoints = fillSettings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Δοκιμαστική επεξεργασία
    fillSettings.Color = Color.Green;

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
    var colorPoint = fillSettings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Αλλαγή θέσης προηγούμενου σημείου
    fillSettings.ColorPoints[1].Location = 1899;

    // Προσθήκη νέου σημείου διαφάνειας
    var transparencyPoint = fillSettings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Αλλαγή θέσης προηγούμενου σημείου διαφάνειας
    fillSettings.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Δοκιμή αρχείου μετά την επεξεργασία
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Green, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Ελέγξτε τα σημεία χρώματος
    AssertAreEqual(3, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Ελέγξτε τα διαφανή σημεία
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Δείτε επίσης

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* συνέλευση [Aspose.PSD](../../)


