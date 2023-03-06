---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage methode. Voegt een omgekeerde aanpassingslaag toe.
type: docs
weight: 360
url: /nl/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Voegt een omgekeerde aanpassingslaag toe.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Winstwaarde

De gemaakte omkeerlaag

### Voorbeelden

De volgende code demonstreert ondersteuning voor de InvertAdjustmentLayer en hoe u InvertAdjustmentLayer toevoegt.

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

### Zie ook

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)


