---
title: BlackWhiteAdjustmentLayer.Magentas
second_title: Aspose.PSD για Αναφορά API .NET
description: BlackWhiteAdjustmentLayer ιδιοκτησία. Λαμβάνει ή ορίζει την τιμή magentas.
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/magentas/
---
## BlackWhiteAdjustmentLayer.Magentas property

Λαμβάνει ή ορίζει την τιμή magentas.

```csharp
public int Magentas { get; set; }
```

### Αξία περιουσίας

Η τιμή magentas.

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

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να χειριστείτε τις ιδιότητες του επιπέδου προσαρμογής μαύρου λευκού στο Aspose.PSD

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### Δείτε επίσης

* class [BlackWhiteAdjustmentLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* συνέλευση [Aspose.PSD](../../../)


