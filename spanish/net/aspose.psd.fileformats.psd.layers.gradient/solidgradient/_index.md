---
title: "Clase SolidGradient"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.SolidGradient class. Configuración de efecto de relleno de degradado"
type: docs
weight: 2230
url: /es/net/aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---
{{< psd/tize >}}
## SolidGradient class

Configuración del efecto de relleno de degradado.

```csharp
public class SolidGradient : BaseGradient
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SolidGradient](solidgradient/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/colorpoints/) { get; set; } | Obtiene o establece los puntos de color. |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/gradientmode/) { get; } | Obtiene el modo para este degradado. Determina 'Tipo de Degradado' = 'Sólido/Ruido' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | Obtiene o establece el nombre del degradado. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/interpolation/) { get; set; } | Obtiene o establece la Interpolación. Determina la suavidad cuando 'Gradient Type' = 'Solid'. Rango de valores: 0-4096. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/transparencypoints/) { get; set; } | Obtiene o establece los puntos de transparencia. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addcolorpoint/)() | Agrega el punto de color. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addtransparencypoint/)() | Agrega el punto de color. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removecolorpoint/)(IGradientColorPoint) | Elimina el punto de color. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removetransparencypoint/)(IGradientTransparencyPoint) | Elimina el punto de transparencia. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/generatelfx2resourcenodes/)() | Genera los nodos de recursos LFX2. |

## Ejemplos

Demuestra la lectura y modificación de la configuración de degradados de ruido y sólido en los efectos de relleno de trazo.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Verificar propiedades comunes de configuración de relleno de degradado
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Verificar propiedades del degradado de Ruido
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

    // Cambiar la configuración del degradado
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

// Verificar los cambios guardados
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Verificar propiedades comunes de configuración de relleno de degradado
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

### Ver también

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


