---
title: "Class NoiseGradient"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.NoiseGradient class. Noise gradient definitieklasse"
type: docs
weight: 2220
url: /nl/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/
---
{{< psd/tize >}}
## NoiseGradient class

Noise gradient definitieklasse.

```csharp
public class NoiseGradient : BaseGradient
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [NoiseGradient](noisegradient/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/colormodel/) { get; set; } | Haalt op of stelt het kleurmodel - RGB/HSB/LAB (3/4/6) in. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/) { get; set; } | Haalt op of stelt het uitbreidingsaantal ( = 2 voor Photoshop 6.0) in. |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/gradientmode/) { get; } | Haalt de modus voor deze gradient op. Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | Haalt een waarde op of stelt de naam van de gradient in. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/maximumcolor/) { get; set; } | Haalt op of stelt de maximale kleur van PixelDataFormat in. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/minimumcolor/) { get; set; } | Haalt op of stelt de minimale kleur van PixelDataFormat in. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/rndnumberseed/) { get; set; } | Haalt op of stelt de willekeurige getal-seed in die wordt gebruikt om kleuren voor Noise gradient te genereren. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/roughness/) { get; set; } | Haalt op of stelt de ruwheidsfactor in. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/showtransparency/) { get; set; } | Haalt op of stelt de vlag voor het tonen van transparantie in. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/usevectorcolor/) { get; set; } | Haalt op of stelt de vlag voor het gebruiken van vectorkleur in. |

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

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


