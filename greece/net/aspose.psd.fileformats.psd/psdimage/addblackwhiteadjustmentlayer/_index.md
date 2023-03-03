---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Προσθέτει το μαύρο λευκό επίπεδο προσαρμογής.
type: docs
weight: 290
url: /el/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Προσθέτει το μαύρο λευκό επίπεδο προσαρμογής.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Επιστρεφόμενη Αξία

Το δημιουργημένο στρώμα προσαρμογής μαύρου λευκού.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να προσθέσετε το στρώμα προσαρμογής μαύρου λευκού κατά το χρόνο εκτέλεσης στο Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

### Δείτε επίσης

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


