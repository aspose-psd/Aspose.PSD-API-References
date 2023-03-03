---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD per riferimento API .NET
description: PsdImage metodo. Aggiunge il livello di regolazione Vividezza.
type: docs
weight: 430
url: /it/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Aggiunge il livello di regolazione Vividezza.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Valore di ritorno

Un livello Vividezza appena creato.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)


