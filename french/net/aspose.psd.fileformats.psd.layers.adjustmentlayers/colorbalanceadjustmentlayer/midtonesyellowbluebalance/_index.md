---
title: ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance
second_title: Référence de l'API Aspose.PSD pour .NET
description: ColorBalanceAdjustmentLayer propriété. Obtient ou définit la balance des tons moyens jaune bleu.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Obtient ou définit la balance des tons moyens jaune bleu.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Valeur de la propriété

L'équilibre bleu jaune des tons moyens.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Jaune Bleu La balance doit être comprise entre -100 et +100. |

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


