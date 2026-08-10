---
title: "Απαρίθμηση InterpolationMethod"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod απαρίθμηση. Συμπιεσμένες τιμές fourCC για τη μέθοδο παρεμβολής διαβάθμισης Photoshop. Κλειδί περιγραφέα gradientsInterpolationMethod"
type: docs
weight: 2160
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Συμπιεσμένες τιμές fourCC για τη μέθοδο παρεμβολής διαβάθμισης του Photoshop. Κλειδί περιγραφέα: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Κλασικό (προεπιλογή κληρονομίας όταν το κλειδί λείπει). |
| Perceptual | `1348825699` | 'Perc' — Αντιληπτικό. |
| Linear | `1282306592` | 'Lnr ' — Γραμμικό (σημειώστε το κενό στο τέλος). |
| Smooth | `1399680879` | 'Smoo' — Ομαλό. |
| Stripes | `1195986291` | 'GIMs' — Ρίγες. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της απόδοσης διαβάθμισης με τη μέθοδο Smooth.

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
    // Ανάγνωση
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Αλλαγή
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Έλεγχος αποθηκευμένων δεδομένων
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

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


