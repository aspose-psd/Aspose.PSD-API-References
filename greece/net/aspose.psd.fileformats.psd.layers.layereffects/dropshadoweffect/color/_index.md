---
title: DropShadowEffect.Color
second_title: Aspose.PSD για Αναφορά API .NET
description: DropShadowEffect ιδιοκτησία. Παίρνει ή ρυθμίζει το χρώμα.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
## DropShadowEffect.Color property

Παίρνει ή ρυθμίζει το χρώμα.

```csharp
public Color Color { get; set; }
```

### Αξία περιουσίας

Το χρώμα.

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

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* συνέλευση [Aspose.PSD](../../../)


