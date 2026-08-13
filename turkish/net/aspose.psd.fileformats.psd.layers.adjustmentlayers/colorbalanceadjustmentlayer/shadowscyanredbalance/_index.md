---
title: "ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ColorBalanceAdjustmentLayer özelliği. Gölge Camgöbeği Kırmızı Dengesini alır veya ayarlar"
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance property

Gölgelerin Camgöbeği Kırmızı Dengesini alır veya ayarlar.

```csharp
public short ShadowsCyanRedBalance { get; set; }
```

### Property Value

Gölge Camgöbeği Kırmızı Dengesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Gölge Camgöbeği Kırmızı Dengesi -100 ile +100 arasında olmalıdır. |

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


