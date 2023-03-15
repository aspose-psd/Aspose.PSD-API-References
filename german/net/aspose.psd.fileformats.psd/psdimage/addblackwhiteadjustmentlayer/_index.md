---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage methode. Fügt die SchwarzweißAnpassungsebene hinzu.
type: docs
weight: 290
url: /de/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Fügt die Schwarzweiß-Anpassungsebene hinzu.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Rückgabewert

Die erstellte Schwarz-Weiß-Anpassungsebene.

### Beispiele

Das folgende Beispiel zeigt, wie Sie die Schwarz-Weiß-Anpassungsebene zur Laufzeit in Aspose.PSD hinzufügen können

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

### Siehe auch

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


