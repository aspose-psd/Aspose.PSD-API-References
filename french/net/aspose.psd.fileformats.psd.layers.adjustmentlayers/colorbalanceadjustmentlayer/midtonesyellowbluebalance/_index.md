---
title: "ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ColorBalanceAdjustmentLayer. Obtient ou définit l'équilibre Jaune Bleu des tons moyens."
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Obtient ou définit le Midtones Yellow Blue Balance.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Property Value

L'équilibre Jaune Bleu des tons moyens.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | L'équilibre Jaune Bleu des tons moyens doit être compris entre -100 et +100. |

## Exemples

Le code suivant démontre la prise en charge de la ColorBalanceAdjustmentLayer.

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

### Voir aussi

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


