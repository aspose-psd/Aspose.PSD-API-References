---
title: Class BlendingOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions τάξη. BlendingOptions. Είναι ένα περιτύλιγμα για το Lfx2Resource που παρέχει api για εφέ επιπέδου
type: docs
weight: 2100
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

BlendingOptions. Είναι ένα περιτύλιγμα για το Lfx2Resource που παρέχει api για εφέ επιπέδου

```csharp
public class BlendingOptions
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Λαμβάνει τα εφέ. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Προσθέτει την επικάλυψη χρώματος. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Προσθέτει το εφέ drop shadow. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Προσθέτει την επικάλυψη Gradient. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Προσθέτει το εφέ εσωτερικής σκιάς. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Προσθέτει το εφέ εξωτερικής λάμψης. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Προσθέτει την επικάλυψη Μοτίβου. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Προσθέτει το εφέ stroke. |

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει πώς μπορείτε να αλλάξετε τις ρυθμίσεις του εφέ εσωτερικού στρώματος σκιάς.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* συνέλευση [Aspose.PSD](../../)


