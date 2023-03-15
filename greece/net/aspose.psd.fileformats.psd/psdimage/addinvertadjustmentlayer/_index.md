---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Προσθέτει ένα επίπεδο προσαρμογής αντιστροφής.
type: docs
weight: 360
url: /el/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Προσθέτει ένα επίπεδο προσαρμογής αντιστροφής.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Επιστρεφόμενη Αξία

Το δημιουργημένο ανεστραμμένο στρώμα

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη για το InvertAdjustmentLayer και τον τρόπο προσθήκης InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### Δείτε επίσης

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


