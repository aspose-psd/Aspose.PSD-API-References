---
title: "Κλάση BlendingOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions κλάση. BlendingOptions. Είναι ένας περιτύλιγμα για το BaseFxResource που παρέχει API για εφέ στρώσης"
type: docs
weight: 2290
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions. Είναι ένας περιτύλιγμα για το BaseFxResource που παρέχει api για εφέ στρώσης

```csharp
public class BlendingOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης. |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | Λαμβάνει τα εφέ. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Προσθέτει την επικάλυψη χρώματος. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Προσθέτει το εφέ σκιάς απόρριψης. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Προσθέτει την επικάλυψη Gradient. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Προσθέτει το εσωτερικό εφέ σκιάς. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Προσθέτει το εξωτερικό εφέ λάμψης. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Προσθέτει την επικάλυψη Pattern. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Προσθέτει το εφέ γραμμής. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε τις ρυθμίσεις του εφέ εσωτερικής σκιάς στρώσης.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


