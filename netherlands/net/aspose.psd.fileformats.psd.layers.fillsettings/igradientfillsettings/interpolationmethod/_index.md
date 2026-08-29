---
title: "IGradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "IGradientFillSettings eigenschap. Haalt op of stelt de interpolatiemethode voor de gradient in"
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## IGradientFillSettings.InterpolationMethod property

Haalt een waarde op of stelt de interpolatiemethode voor de gradient in.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Voorbeelden

De volgende code demonstreert de ondersteuning van gradientrendering met de Smooth-methode.

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
    // Lezen
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Wijzigen
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Controleer opgeslagen gegevens
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

### Zie ook

* enum [InterpolationMethod](../../interpolationmethod/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


