---
title: "Klasse GradientMapSettings"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientMapSettings class. Gradientinstellingenklasse voor gradientmaplaag. Het bevat gemeenschappelijke eigenschappen voor beide typen gradient Solid en Noise"
type: docs
weight: 2080
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/
---
{{< psd/tize >}}
## GradientMapSettings class

Gradientinstellingenklasse voor gradientmaplaag. Het bevat gemeenschappelijke eigenschappen voor beide typen gradient (Solid en Noise).

```csharp
public class GradientMapSettings
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GradientMapSettings](gradientmapsettings/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/dither/) { get; set; } | Haalt een waarde op of stelt een waarde in die aangeeft of dit [`GradientFillSettings`](../gradientfillsettings/) dither is. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/gradient/) { get; set; } | Haalt een waarde op of stelt een specifieke gradientdefinitie‑instantie in (Solid/Noise). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/) { get; set; } | Haalt een waarde op of stelt de interpolatiemethode voor de gradient in. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/reverse/) { get; set; } | Haalt een waarde op of stelt een waarde in die aangeeft of dit [`GradientFillSettings`](../gradientfillsettings/) omgekeerd is. |

## Voorbeelden

Toont het lezen en aanpassen van noise- en solid-gradientinstellingen in penseelvullingseffecten.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Controleer gemeenschappelijke eigenschappen van gradientvullinginstellingen
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Controleer Noise-gradienteigenschappen
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

    // Wijzig gradientinstellingen
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

// Controleer opgeslagen wijzigingen
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Controleer gemeenschappelijke eigenschappen van gradientvullinginstellingen
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

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


