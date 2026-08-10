---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "BlackWhiteAdjustmentLayer ιδιότητα. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το χρώμα απόχρωσης χρησιμοποιείται"
type: docs
weight: 120
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [tint color] χρησιμοποιείται.

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` εάν χρησιμοποιείται [tint color]; διαφορετικά, `false`.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να διαχειριστείτε τις ιδιότητες του στρώματος ρυθμίσεων ασπρόμαυρου στο Aspose.PSD

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


