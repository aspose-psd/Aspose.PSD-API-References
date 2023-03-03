---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD per riferimento API .NET
description: PsdImage metodo. Aggiunge un livello di regolazione invertito.
type: docs
weight: 360
url: /it/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Aggiunge un livello di regolazione invertito.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Valore di ritorno

Il livello invertito creato

### Esempi

Il codice seguente illustra il supporto per InvertAdjustmentLayer e come aggiungere InvertAdjustmentLayer.

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

### Guarda anche

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)


