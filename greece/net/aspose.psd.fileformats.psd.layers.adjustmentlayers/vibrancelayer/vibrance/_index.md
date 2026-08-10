---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα VibranceLayer. Λαμβάνει ή ορίζει τη ζωντάνια"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Αποκτά ή ορίζει τη ζωντάνια.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Η ζωντάνια.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Η ζωντάνια πρέπει να είναι στο εύρος από -180 έως +180 |

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα δείχνει την υποστήριξη της στρώσης VibranceLayer και τη δυνατότητα επεξεργασίας αυτής της ρύθμισης.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Δημιουργία μιας νέας VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Δείτε επίσης

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


