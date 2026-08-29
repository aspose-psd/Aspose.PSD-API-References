---
title: "Κλάση InnerShadowEffect"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect κλάση. Εφέ εσωτερικής σκιάς στρώσης"
type: docs
weight: 2350
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Εφέ στρώσης Εσωτερικής Σκιάς

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία σε μοίρες. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση σε εικονοστοιχεία. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Λαμβάνει έναν τύπο εφέ |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Λαμβάνει ή ορίζει τον θόρυβο. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Λαμβάνει ή ορίζει την τιμή θολώματος σε εικονοστοιχεία. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Λαμβάνει ή ορίζει το εύρος (σφίξιμο) ως ποσοστό. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [use this angle in all of the layer effects]. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου της στρώσης. |

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

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


