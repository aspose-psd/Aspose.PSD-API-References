---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα VibranceLayer. Λαμβάνει ή ορίζει τον κορεσμό"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

Αποκτά ή ορίζει τον κορεσμό.

```csharp
public int Saturation { get; set; }
```

### Property Value

Ο κορεσμός.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Ο κορεσμός πρέπει να είναι στο εύρος από -100 έως +100 |

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


