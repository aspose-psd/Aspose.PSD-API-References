---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD für .NET-API-Referenz
description: ColorBalanceAdjustmentLayer eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob dies der Fall istBlncResource bewahrt die Leuchtkraft.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) bewahrt die Leuchtkraft.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Eigentumswert

`WAHR` wenn es die Leuchtkraft bewahrt; ansonsten,`FALSCH` .

### Beispiele

Der folgende Code demonstriert die Unterstützung für ColorBalanceAdjustmentLayer.

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

### Siehe auch

* class [ColorBalanceAdjustmentLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* Montage [Aspose.PSD](../../../)


