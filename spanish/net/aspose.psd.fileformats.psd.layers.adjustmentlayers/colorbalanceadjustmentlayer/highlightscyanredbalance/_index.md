---
title: "ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad ColorBalanceAdjustmentLayer. Obtiene o establece el Balance de Cian/Rojo de los Destacados"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightscyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance property

Obtiene o establece el balance Cyan Rojo de Highlights.

```csharp
public short HighlightsCyanRedBalance { get; set; }
```

### Property Value

El Balance de Cian/Rojo de los Destacados.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El Balance de Cian/Rojo de los Destacados debe estar en el rango de -100 a +100. |

## Ejemplos

El siguiente código demuestra el soporte para la ColorBalanceAdjustmentLayer.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


