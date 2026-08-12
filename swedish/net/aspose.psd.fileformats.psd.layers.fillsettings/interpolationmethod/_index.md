---
title: "Enum InterpolationMethod"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod-enum. Packade fourCC-värden för Photoshop-gradientinterpolationsmetod. Deskriptörnyckel gradientsInterpolationMethod"
type: docs
weight: 2160
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Packade fourCC-värden för Photoshop gradientinterpolationsmetod. Deskriptörnyckel: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Klassisk (standardvärde från äldre version när nyckeln saknas). |
| Perceptual | `1348825699` | 'Perc' — Perceptuell. |
| Linear | `1282306592` | 'Lnr ' — Linjär (observera efterföljande mellanslag). |
| Smooth | `1399680879` | 'Smoo' — Mjuk. |
| Stripes | `1195986291` | 'GIMs' — Ränder. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


