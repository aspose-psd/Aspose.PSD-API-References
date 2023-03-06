---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD för .NET API-referens
description: PsdImage metod. Lägger till ett inverteringsjusteringslager.
type: docs
weight: 360
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Lägger till ett inverteringsjusteringslager.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Returvärde

Det skapade inverteringsskiktet

### Exempel

Följande kod visar stöd för InvertAdjustmentLayer och hur man lägger till InvertAdjustmentLayer.

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

### Se även

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


