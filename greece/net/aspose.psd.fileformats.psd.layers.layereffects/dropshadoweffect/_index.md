---
title: Class DropShadowEffect
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect τάξη. Drop Shadow Layer effect
type: docs
weight: 2120
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Drop Shadow Layer effect

```csharp
public class DropShadowEffect : IShadowEffect
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Λαμβάνει ή ρυθμίζει τη γωνία σε μοίρες. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία ανάμειξης. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Παίρνει ή ρυθμίζει το χρώμα. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση σε pixel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Λαμβάνει έναν τύπο εφέ |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Λαμβάνει ή ρυθμίζει το θόρυβο. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Λαμβάνει ή ορίζει την αδιαφάνεια. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Λαμβάνει ή ορίζει την τιμή θαμπώματος σε pixel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Λαμβάνει ή ορίζει την ένταση ως ποσοστό. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [χρησιμοποιήστε αυτήν τη γωνία σε όλα τα εφέ επιπέδου]. |

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει υποστήριξη για την ιδιότητα PsdImage.GlobalAngle για την αλλαγή της τιμής καθολικής γωνίας.

```csharp
[C#]

// Όταν η ιδιότητα DropShadowEffect.UseGlobalLight είναι "true", τότε το αντικείμενο DropShadowEffect χρησιμοποιεί την τιμή γωνίας από την ιδιότητα PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Ο παρακάτω κώδικας δείχνει τη χρήση της ιδιότητας Opacity του DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Παράδειγμα με Αδιαφάνεια = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Παράδειγμα με Αδιαφάνεια = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Δείτε επίσης

* interface [IShadowEffect](../ishadoweffect/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* συνέλευση [Aspose.PSD](../../)


