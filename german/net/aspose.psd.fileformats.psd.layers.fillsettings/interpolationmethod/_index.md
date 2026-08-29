---
title: "Enum InterpolationMethod"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod enum. Gepackte fourCC-Werte für die Photoshop-Gradient-Interpolationsmethode. Deskriptorschlüssel gradientsInterpolationMethod"
type: docs
weight: 2160
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Gepackte fourCC‑Werte für die Photoshop‑Gradient‑Interpolationsmethode. Deskriptorschlüssel: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Klassisch (Standardwert bei fehlendem Schlüssel). |
| Perceptual | `1348825699` | 'Perc' — Perzeptuell. |
| Linear | `1282306592` | 'Lnr ' — Linear (Hinweis: nachfolgendes Leerzeichen). |
| Smooth | `1399680879` | 'Smoo' — Glatt. |
| Stripes | `1195986291` | 'GIMs' — Streifen. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Gradienten‑Renderung mit der Smooth‑Methode.

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
    // Lesen
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Ändern
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Gespeicherte Daten prüfen
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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


