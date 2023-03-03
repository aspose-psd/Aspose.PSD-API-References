---
title: DropShadowEffect.Angle
second_title: Aspose.PSD για Αναφορά API .NET
description: DropShadowEffect ιδιοκτησία. Λαμβάνει ή ρυθμίζει τη γωνία σε μοίρες.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

Λαμβάνει ή ρυθμίζει τη γωνία σε μοίρες.

```csharp
public int Angle { get; set; }
```

### Αξία περιουσίας

Η γωνία.

### Παραδείγματα

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

* class [DropShadowEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* συνέλευση [Aspose.PSD](../../../)


