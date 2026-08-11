---
title: "Classe GradientMapSettings"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientMapSettings classe. Classe delle impostazioni di gradiente per il livello mappa gradiente. Contiene proprietà comuni per entrambi i tipi di gradiente Solido e Rumore."
type: docs
weight: 2080
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/
---
{{< psd/tize >}}
## GradientMapSettings class

Classe delle impostazioni di gradiente per il livello mappa gradiente. Contiene proprietà comuni per entrambi i tipi di gradiente (Solido e Rumore).

```csharp
public class GradientMapSettings
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GradientMapSettings](gradientmapsettings/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/dither/) { get; set; } | Ottiene o imposta un valore che indica se questo [`GradientFillSettings`](../gradientfillsettings/) è dither. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/gradient/) { get; set; } | Ottiene o imposta l'istanza di definizione del gradiente specifico (Solido/Rumore). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/) { get; set; } | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/reverse/) { get; set; } | Ottiene o imposta un valore che indica se questo [`GradientFillSettings`](../gradientfillsettings/) è invertito. |

## Esempi

Dimostra la lettura e la modifica delle impostazioni di gradiente rumore e solido negli effetti di riempimento del tratto.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Verifica le proprietà comuni delle impostazioni di riempimento del gradiente
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Verifica le proprietà del gradiente Rumore
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

    // Modifica le impostazioni del gradiente
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

// Verifica le modifiche salvate
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Verifica le proprietà comuni delle impostazioni di riempimento del gradiente
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

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


