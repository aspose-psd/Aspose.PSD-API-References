---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "GradientColorPoint κατασκευαστής. Δημιουργεί ένα νέο στιγμιότυπο της κλάσης GradientColorPoint"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### Δείτε επίσης

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| χρώμα | Χρώμα | Σημείο χρώματος στη διαβάθμιση. |
| τοποθεσία | Int32 | Η τοποθεσία του σημείου χρώματος στη διαβάθμιση. |
| medianPointLocation | Int32 | Η τοποθεσία του μεσαίου σημείου διαβάθμισης. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε/επεξεργαστείτε το αντικείμενο εφέ GradientOverlayEffect σε ένα επίπεδο.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Δημιουργεί/Αποκτά και επεξεργάζεται το εφέ επικάλυψης διαβάθμισης σε ένα επίπεδο.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Αναζητήστε GradientOverlayEffect σε ένα επίπεδο.
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // Μπορείτε να δημιουργήσετε ένα νέο GradientOverlayEffect εάν δεν υπάρχει.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Προσθέστε λίγο διαφάνεια στο εφέ.
    gradientOverlayEffect.Opacity = 200;

    // Αλλάξτε τη λειτουργία ανάμειξης του εφέ διαβάθμισης.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Λαμβάνει το αντικείμενο GradientFillSettings για να διαμορφώσει τις ρυθμίσεις επικάλυψης διαβάθμισης.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Ορίζοντας μια νέα διαβάθμιση με δύο χρώματα.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Ορίζει κλίση της διαβάθμισης σε γωνία 80 μοιρών.
    settings.Angle = 80;

    // Κλιμακώνει το εφέ διαβάθμισης έως 150%.
    settings.Scale = 150;

    // Ορίζει τύπο διαβάθμισης.
    settings.GradientType = GradientType.Linear;

    // Κάντε τη διαβάθμιση αδιαφανή ορίζοντας την αδιαφάνεια στο 100% σε κάθε σημείο διαφάνειας.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Δείτε επίσης

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


