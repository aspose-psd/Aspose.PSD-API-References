---
title: VibranceLayer.Saturation
second_title: Aspose.PSD per riferimento API .NET
description: VibranceLayer proprietà. Ottiene o imposta la saturazione.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Ottiene o imposta la saturazione.

```csharp
public int Saturation { get; set; }
```

### Valore della proprietà

La saturazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | La saturazione deve essere compresa tra -100 e +100 |

### Esempi

L'esempio di codice seguente illustra il supporto del livello VibranceLayer e la possibilità di modificare questa regolazione.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Creazione di un nuovo VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Guarda anche

* class [VibranceLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* assemblea [Aspose.PSD](../../../)


