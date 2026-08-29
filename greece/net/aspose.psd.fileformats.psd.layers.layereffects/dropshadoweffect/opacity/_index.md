---
title: "DropShadowEffect.Opacity"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα DropShadowEffect. Λαμβάνει ή ορίζει τη διαφάνεια"
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/
---
{{< psd/tize >}}
## DropShadowEffect.Opacity property

Λαμβάνει ή ορίζει τη διαφάνεια.

```csharp
public byte Opacity { get; set; }
```

### Property Value

Η διαφάνεια.

## Παραδείγματα

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

    // Παράδειγμα με Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Παράδειγμα με Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Δείτε επίσης

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


