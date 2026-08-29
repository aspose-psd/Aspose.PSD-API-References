---
title: "BlackWhiteAdjustmentLayer.Blues"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα BlackWhiteAdjustmentLayer. Λαμβάνει ή ορίζει την τιμή των μπλε."
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blues/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.Blues property

Λαμβάνει ή ορίζει την τιμή των μπλε.

```csharp
public int Blues { get; set; }
```

### Property Value

Η τιμή των μπλε.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να προσθέσετε το black white adjustment layer κατά την εκτέλεση στο Aspose.PSD

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


