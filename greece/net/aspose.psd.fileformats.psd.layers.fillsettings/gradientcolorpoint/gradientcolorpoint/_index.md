---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD για Αναφορά API .NET
description: GradientColorPoint κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουGradientColorPoint τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`GradientColorPoint`](../) τάξη.

```csharp
public GradientColorPoint()
```

### Δείτε επίσης

* class [GradientColorPoint](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* συνέλευση [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`GradientColorPoint`](../) τάξη.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | Color | Σημείο χρώματος στην κλίση. |
| location | Int32 | Η θέση του σημείου χρώματος στη διαβάθμιση. |
| medianPointLocation | Int32 | Η μέση θέση σημείου κλίσης. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να δημιουργήσετε/επεξεργαστείτε το αντικείμενο εφέ GradientOverlayEffect σε επίπεδο.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Δημιουργεί/Λάβει και επεξεργάζεται το εφέ επικάλυψης διαβάθμισης σε ένα επίπεδο.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Αναζήτηση GradientOverlayEffect σε ένα επίπεδο.
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

    // Προσθέστε λίγη διαφάνεια στο εφέ.
    gradientOverlayEffect.Opacity = 200;

    // Αλλαγή του συνδυασμού του εφέ ντεγκραντέ.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Λαμβάνει το αντικείμενο GradientFillSettings για να διαμορφώσει τις ρυθμίσεις επικάλυψης κλίσης.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Ορισμός νέας διαβάθμισης με δύο χρώματα.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Ορίζει μια κλίση της κλίσης σε γωνία 80 μοιρών.
    settings.Angle = 80;

    // Κλίμακα εφέ κλίσης έως και 150%.
    settings.Scale = 150;

    // Ορίζει τον τύπο της κλίσης.
    settings.GradientType = GradientType.Linear;

    // Κάντε την κλίση αδιαφανή ορίζοντας την αδιαφάνεια στο 100% σε κάθε σημείο διαφάνειας.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Δείτε επίσης

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* συνέλευση [Aspose.PSD](../../../)


