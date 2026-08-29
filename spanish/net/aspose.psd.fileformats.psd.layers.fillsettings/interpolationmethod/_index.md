---
title: "Enumeración InterpolationMethod"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod. Valores fourCC empaquetados para el método de interpolación de gradiente de Photoshop. Clave del descriptor gradientsInterpolationMethod"
type: docs
weight: 2160
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Valores fourCC empaquetados para el método de interpolación de degradado de Photoshop. Clave del descriptor: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Clásico (valor predeterminado heredado cuando la clave está ausente). |
| Perceptual | `1348825699` | 'Perc' — Perceptual. |
| Linear | `1282306592` | 'Lnr ' — Lineal (nota espacio al final). |
| Smooth | `1399680879` | 'Smoo' — Suave. |
| Stripes | `1195986291` | 'GIMs' — Rayas. |

## Ejemplos

El siguiente código demuestra el soporte de renderizado de degradado con el método Smooth.

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // Leer
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Cambiar
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Verificar datos guardados
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


