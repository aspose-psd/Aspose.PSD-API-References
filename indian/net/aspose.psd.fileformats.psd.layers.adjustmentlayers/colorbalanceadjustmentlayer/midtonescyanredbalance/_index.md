---
title: "ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ColorBalanceAdjustmentLayer प्रॉपर्टी। Midtones Cyan Red Balance को प्राप्त करता है या सेट करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

मिडटोन सियान रेड बैलेंस को प्राप्त करता है या सेट करता है।

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

यह Midtones Cyan Red Balance।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Cyan Red Balance -100 से +100 की सीमा में होना चाहिए। |

## उदाहरण

निम्नलिखित कोड ColorBalanceAdjustmentLayer के समर्थन को दर्शाता है।

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

### देखें भी

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


