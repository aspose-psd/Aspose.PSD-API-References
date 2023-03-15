---
title: ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance
second_title: Référence de l'API Aspose.PSD pour .NET
description: ColorBalanceAdjustmentLayer propriété. Obtient ou définit la balance Ombres Cyan Rouge.
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance property

Obtient ou définit la balance Ombres Cyan Rouge.

```csharp
public short ShadowsCyanRedBalance { get; set; }
```

### Valeur de la propriété

L'équilibre des ombres cyan rouge.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Cyan Red Balance doit être compris entre -100 et +100. |

### Exemples

Le code suivant illustre la prise en charge de ColorBalanceAdjustmentLayer.

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

### Voir également

* class [ColorBalanceAdjustmentLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* Assemblée [Aspose.PSD](../../../)


