---
title: "ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad ColorBalanceAdjustmentLayer. Obtiene o establece el Equilibrio de Cian Rojo de Tonos Medios"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

Obtiene o establece el balance Cyan Rojo de Midtones.

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

El Equilibrio de Cian Rojo de Tonos Medios.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El Equilibrio de Cian Rojo de Tonos Medios debe estar en el rango de -100 a +100. |

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


