---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Fügt eine Invertierungs-Anpassungsebene hinzu."
type: docs
weight: 380
url: /de/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Fügt eine Invertierungs-Anpassungsebene hinzu.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Rückgabewert

Die erstellte Invertierungsebene

## Beispiele

Der folgende Code demonstriert die Unterstützung für die InvertAdjustmentLayer und wie man InvertAdjustmentLayer hinzufügt.

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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


