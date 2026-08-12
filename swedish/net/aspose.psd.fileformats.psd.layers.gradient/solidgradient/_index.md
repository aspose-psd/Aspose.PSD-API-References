---
title: "Klass SolidGradient"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.SolidGradient klass. Inställningar för gradientfyllningseffekt"
type: docs
weight: 2230
url: /sv/net/aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---
{{< psd/tize >}}
## SolidGradient class

Inställningar för gradientfyllningseffekt.

```csharp
public class SolidGradient : BaseGradient
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SolidGradient](solidgradient/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/colorpoints/) { get; set; } | Hämtar eller anger färgpunkterna. |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/gradientmode/) { get; } | Hämtar läget för denna gradient. Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | Hämtar eller anger gradientens namn. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/interpolation/) { get; set; } | Hämtar eller anger Interpolation. Bestämmer jämnhet när 'Gradient Type' = 'Solid'. Värdeintervall: 0-4096. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/transparencypoints/) { get; set; } | Hämtar eller anger transparenspunkterna. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addcolorpoint/)() | Lägger till färgpunkten. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addtransparencypoint/)() | Lägger till färgpunkten. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removecolorpoint/)(IGradientColorPoint) | Tar bort färgpunkten. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removetransparencypoint/)(IGradientTransparencyPoint) | Tar bort transparenspunkten. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/generatelfx2resourcenodes/)() | Genererar LFX2-resursnoderna. |

## Exempel

Demonstrerar läsning och modifiering av brus- och solidgradientinställningar i strokefyllningseffekter.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Kontrollera gemensamma egenskaper för gradientfyllningsinställningar
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Kontrollera brusgradientens egenskaper
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

    // Ändra gradientinställningar
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

// Kontrollera sparade ändringar
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Kontrollera gemensamma egenskaper för gradientfyllningsinställningar
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

### Se även

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


