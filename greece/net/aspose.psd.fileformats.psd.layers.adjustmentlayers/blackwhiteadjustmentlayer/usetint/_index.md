---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD για Αναφορά API .NET
description: BlackWhiteAdjustmentLayer ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται χρώμα απόχρωσης.
type: docs
weight: 120
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται [χρώμα απόχρωσης].

```csharp
public bool UseTint { get; set; }
```

### Αξία περιουσίας

`αληθής` εάν χρησιμοποιείται [χρώμα απόχρωσης]. σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

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


