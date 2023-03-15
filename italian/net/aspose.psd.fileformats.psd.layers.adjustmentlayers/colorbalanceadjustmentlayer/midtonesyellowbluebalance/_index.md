---
title: ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance
second_title: Aspose.PSD per riferimento API .NET
description: ColorBalanceAdjustmentLayer proprietà. Ottiene o imposta il bilanciamento giallo blu dei mezzitoni.
type: docs
weight: 60
url: /it/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Ottiene o imposta il bilanciamento giallo blu dei mezzitoni.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Valore della proprietà

Il bilanciamento giallo blu dei mezzitoni.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Mezzitoni Giallo Blu Il bilanciamento deve essere compreso tra -100 e +100. |

### Esempi

Il codice seguente illustra il supporto per ColorBalanceAdjustmentLayer.

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### Guarda anche

* class [ColorBalanceAdjustmentLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* assemblea [Aspose.PSD](../../../)


