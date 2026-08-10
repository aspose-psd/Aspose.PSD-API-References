---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PsdImage. Προσθέτει το επίπεδο προσαρμογής ασπρόμαυρου"
type: docs
weight: 300
url: /el/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

Προσθέτει το επίπεδο προσαρμογής ασπρόμαυρου.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Τιμή Επιστροφής

Το δημιουργημένο επίπεδο προσαρμογής ασπρόμαυρου.

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

### Δείτε επίσης

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


