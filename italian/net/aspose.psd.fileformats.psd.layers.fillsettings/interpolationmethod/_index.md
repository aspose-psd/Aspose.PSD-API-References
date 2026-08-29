---
title: "Enum InterpolationMethod"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod enum. Valori fourCC impacchettati per il metodo di interpolazione del gradiente di Photoshop. Chiave del descrittore gradientsInterpolationMethod"
type: docs
weight: 2160
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Valori fourCC impacchettati per il metodo di interpolazione del gradiente di Photoshop. Chiave del descrittore: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Classico (predefinito legacy quando la chiave è assente). |
| Perceptual | `1348825699` | 'Perc' — Percepito. |
| Linear | `1282306592` | 'Lnr ' — Lineare (nota lo spazio finale). |
| Smooth | `1399680879` | 'Smoo' — Liscio. |
| Stripes | `1195986291` | 'GIMs' — Strisce. |

## Esempi

Il codice seguente dimostra il supporto del rendering del gradiente con il metodo Smooth.

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
    // Leggi
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Modifica
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Verifica i dati salvati
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

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


