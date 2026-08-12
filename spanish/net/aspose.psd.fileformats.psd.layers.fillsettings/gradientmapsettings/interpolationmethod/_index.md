---
title: "GradientMapSettings.InterpolationMethod"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad GradientMapSettings. Obtiene o establece el método de interpolación para el gradiente"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientMapSettings.InterpolationMethod property

Obtiene o establece el método de interpolación para el degradado.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

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

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientMapSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


