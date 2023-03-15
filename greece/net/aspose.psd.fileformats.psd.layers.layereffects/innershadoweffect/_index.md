---
title: Class InnerShadowEffect
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect τάξη. Εφέ εσωτερικού στρώματος σκιάς
type: docs
weight: 2160
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Εφέ εσωτερικού στρώματος σκιάς

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Λαμβάνει ή ρυθμίζει τη γωνία σε μοίρες. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία ανάμειξης. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Παίρνει ή ρυθμίζει το χρώμα. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση σε pixel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Λαμβάνει έναν τύπο εφέ |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Λαμβάνει ή ρυθμίζει το θόρυβο. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Λαμβάνει ή ορίζει την αδιαφάνεια. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Λαμβάνει ή ορίζει την τιμή θαμπώματος σε pixel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Λαμβάνει ή ορίζει το spread (τσοκ) ως ποσοστό. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [χρησιμοποιήστε αυτήν τη γωνία σε όλα τα εφέ επιπέδου]. |

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

* interface [IShadowEffect](../ishadoweffect/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* συνέλευση [Aspose.PSD](../../)


