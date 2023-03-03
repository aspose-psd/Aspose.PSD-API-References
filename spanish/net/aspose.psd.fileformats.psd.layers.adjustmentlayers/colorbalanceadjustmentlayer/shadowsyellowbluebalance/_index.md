---
title: ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance
second_title: Referencia de API de Aspose.PSD para .NET
description: ColorBalanceAdjustmentLayer propiedad. Obtiene o establece Shadows YellowBlue Balance.
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance property

Obtiene o establece Shadows YellowBlue Balance.

```csharp
public short ShadowsYellowBlueBalance { get; set; }
```

### El valor de la propiedad

Las Sombras Amarillo Azul Equilibrio.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Yellow Blue Balance debe estar en el rango de -100 a +100. |

### Ejemplos

El siguiente código demuestra la compatibilidad con ColorBalanceAdjustmentLayer.

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

### Ver también

* class [ColorBalanceAdjustmentLayer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* asamblea [Aspose.PSD](../../../)


