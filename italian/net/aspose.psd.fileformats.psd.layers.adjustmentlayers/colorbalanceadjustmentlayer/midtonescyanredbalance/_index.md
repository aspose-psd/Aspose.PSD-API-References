---
title: ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance
second_title: Aspose.PSD per riferimento API .NET
description: ColorBalanceAdjustmentLayer proprietà. Ottiene o imposta il bilanciamento del rosso ciano dei mezzitoni.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

Ottiene o imposta il bilanciamento del rosso ciano dei mezzitoni.

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Valore della proprietà

Il bilanciamento del rosso ciano dei mezzitoni.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Il bilanciamento del rosso ciano dei mezzitoni deve essere compreso tra -100 e +100. |

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


