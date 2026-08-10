---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "PsdImage μέθοδος. Προσθέτει ένα στρώμα ρύθμισης αντιστροφής"
type: docs
weight: 380
url: /el/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Προσθέτει ένα επίπεδο προσαρμογής αντιστροφής.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Τιμή Επιστροφής

Το δημιουργημένο στρώμα αντιστροφής

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη για το InvertAdjustmentLayer και πώς να προσθέσετε το InvertAdjustmentLayer.

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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


