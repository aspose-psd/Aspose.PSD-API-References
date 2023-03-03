---
title: VibranceLayer.Saturation
second_title: Aspose.PSD για Αναφορά API .NET
description: VibranceLayer ιδιοκτησία. Λαμβάνει ή ρυθμίζει τον κορεσμό.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Λαμβάνει ή ρυθμίζει τον κορεσμό.

```csharp
public int Saturation { get; set; }
```

### Αξία περιουσίας

Ο κορεσμός.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Ο κορεσμός πρέπει να κυμαίνεται από -100 έως +100 |

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


