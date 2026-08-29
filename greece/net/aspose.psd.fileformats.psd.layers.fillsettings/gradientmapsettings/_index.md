---
title: "Κλάση GradientMapSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientMapSettings κλάση. Κλάση ρυθμίσεων διαβάθμισης για το επίπεδο χάρτη διαβάθμισης. Περιέχει κοινές ιδιότητες για και τους δύο τύπους διαβάθμισης Solid και Noise"
type: docs
weight: 2080
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/
---
{{< psd/tize >}}
## GradientMapSettings class

Κλάση ρυθμίσεων διαβάθμισης για το επίπεδο χάρτη διαβάθμισης. Περιέχει κοινές ιδιότητες για και τους δύο τύπους διαβάθμισης (Σταθερή και Θόρυβος).

```csharp
public class GradientMapSettings
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GradientMapSettings](gradientmapsettings/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/dither/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [`GradientFillSettings`](../gradientfillsettings/) είναι dither. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/gradient/) { get; set; } | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/reverse/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [`GradientFillSettings`](../gradientfillsettings/) είναι αντίστροφο. |

## Παραδείγματα

Δείχνει την ανάγνωση και τροποποίηση των ρυθμίσεων διαβάθμισης noise και solid στα εφέ γεμίσματος γραμμής.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Έλεγχος κοινών ιδιοτήτων ρυθμίσεων διαβάθμισης γεμίσματος
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Έλεγχος ιδιοτήτων διαβάθμισης Noise
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // Αλλάξτε τις ρυθμίσεις διαβάθμισης
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// Ελέγξτε τις αποθηκευμένες αλλαγές
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Έλεγχος κοινών ιδιοτήτων ρυθμίσεων διαβάθμισης γεμίσματος
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


