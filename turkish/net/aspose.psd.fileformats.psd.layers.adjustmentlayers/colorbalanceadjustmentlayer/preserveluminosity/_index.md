---
title: "ColorBalanceAdjustmentLayer.PreserveLuminosity"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ColorBalanceAdjustmentLayer özelliği. Bu BlncResource'un parlaklığı koruyup korumadığını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Bu [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) parlaklığı koruyup korumadığını gösteren bir değeri alır veya ayarlar.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` eğer parlaklığı koruyorsa; aksi takdirde, `false`.

## Örnekler

Aşağıdaki kod, ColorBalanceAdjustmentLayer desteğini gösterir.

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

### Ayrıca Bakınız

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


