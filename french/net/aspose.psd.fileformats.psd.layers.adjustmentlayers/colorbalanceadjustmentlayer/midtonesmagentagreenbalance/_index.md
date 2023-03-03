---
title: ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance
second_title: Référence de l'API Aspose.PSD pour .NET
description: ColorBalanceAdjustmentLayer propriété. Obtient ou définit léquilibre entre les tons moyens le magenta et le vert.
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

Obtient ou définit l'équilibre entre les tons moyens, le magenta et le vert.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Valeur de la propriété

L'équilibre des tons moyens magenta vert.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Magenta Green Balance doit être compris entre -100 et +100. |

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


