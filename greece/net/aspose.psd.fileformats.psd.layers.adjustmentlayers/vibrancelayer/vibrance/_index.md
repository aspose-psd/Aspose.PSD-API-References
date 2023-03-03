---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD για Αναφορά API .NET
description: VibranceLayer ιδιοκτησία. Λαμβάνει ή ρυθμίζει τη δόνηση.
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

Λαμβάνει ή ρυθμίζει τη δόνηση.

```csharp
public int Vibrance { get; set; }
```

### Αξία περιουσίας

Η δόνηση.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Η δόνηση πρέπει να κυμαίνεται από -180 έως +180 |

### Παραδείγματα

Το ακόλουθο παράδειγμα κώδικα δείχνει την υποστήριξη του επιπέδου VibranceLayer και τη δυνατότητα επεξεργασίας αυτής της προσαρμογής.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Δημιουργία νέου VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Δείτε επίσης

* class [VibranceLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* συνέλευση [Aspose.PSD](../../../)


