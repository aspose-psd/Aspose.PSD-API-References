---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PsdImage. Προσθέτει τη στρώση ρύθμισης Vibrance"
type: docs
weight: 490
url: /el/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Προσθέτει το Vibrance adjustment layer.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Τιμή Επιστροφής

Μια νεοδημιουργημένη στρώση Vibrance.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


