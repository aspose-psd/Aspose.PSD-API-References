---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage methode. Voegt de zwartwitte aanpassingslaag toe.
type: docs
weight: 290
url: /nl/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Voegt de zwart-witte aanpassingslaag toe.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Winstwaarde

De gemaakte zwart-witte aanpassingslaag.

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de zwart-witte aanpassingslaag tijdens runtime kunt toevoegen in Aspose.PSD

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

### Zie ook

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)


