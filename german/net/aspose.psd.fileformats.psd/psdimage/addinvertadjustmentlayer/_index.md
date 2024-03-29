---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage methode. Fügt eine Invertierungsebene hinzu.
type: docs
weight: 360
url: /de/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Fügt eine Invertierungsebene hinzu.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Rückgabewert

Die erstellte Umkehrebene

### Beispiele

Der folgende Code veranschaulicht die Unterstützung für InvertAdjustmentLayer und das Hinzufügen von InvertAdjustmentLayer.

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

### Siehe auch

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


