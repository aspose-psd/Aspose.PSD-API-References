---
title: "GradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GradientFillSettings egenskap. Hämtar eller anger interpolationsmetoden för gradienten"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientFillSettings.InterpolationMethod property

Hämtar eller anger interpolationsmetoden för gradienten.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Exempel

Följande kod demonstrerar stöd för gradientrendering med Smooth-metoden.

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
    // Läs
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Ändra
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Kontrollera sparade data
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

### Se även

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


