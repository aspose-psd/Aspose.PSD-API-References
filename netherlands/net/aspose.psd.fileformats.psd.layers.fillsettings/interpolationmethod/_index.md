---
title: "Enum InterpolationMethod"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod enum. Ingepakte fourCC-waarden voor Photoshop gradient interpolatiemethode. Descriptor‑sleutel gradientsInterpolationMethod"
type: docs
weight: 2160
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Ingepakte fourCC-waarden voor Photoshop gradient interpolatiemethode. Descriptor‑sleutel: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Klassiek (standaardwaarde uit het verleden wanneer sleutel ontbreekt). |
| Perceptual | `1348825699` | 'Perc' — Perceptueel. |
| Linear | `1282306592` | 'Lnr ' — Lineair (let op achterste spatie). |
| Smooth | `1399680879` | 'Smoo' — Glad. |
| Stripes | `1195986291` | 'GIMs' — Strepen. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


