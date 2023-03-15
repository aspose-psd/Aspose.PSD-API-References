---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Référence de l'API Aspose.PSD pour .NET
description: ColorBalanceAdjustmentLayer propriété. Obtient ou définit une valeur indiquant si cetteBlncResource préserve la luminosité.
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Obtient ou définit une valeur indiquant si cette[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) préserve la luminosité.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Valeur de la propriété

`vrai` s'il conserve la luminosité ; sinon,`FAUX` .

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


