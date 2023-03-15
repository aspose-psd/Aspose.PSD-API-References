---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Προσθέτει το επίπεδο προσαρμογής Vibrance.
type: docs
weight: 430
url: /el/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Προσθέτει το επίπεδο προσαρμογής Vibrance.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Επιστρεφόμενη Αξία

Ένα νέο επίπεδο Vibrance που δημιουργήθηκε.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


