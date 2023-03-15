---
title: ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ColorBalanceAdjustmentLayer संपत्त. मडटन येल ब्लू बैलेंस प्रप्त य सेट करत है
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

मिडटोन येलो ब्लू बैलेंस प्राप्त या सेट करता है।

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### संपत्ति मूल्य

द मिडटोन्स येलो ब्लू बैलेंस।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | मिडटोन येलो ब्लू बैलेंस -100 से +100 के बीच होना चाहिए। |

### उदाहरण

निम्न कोड ColorBalanceAdjustmentLayer के लिए समर्थन प्रदर्शित करता है।

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

### यह सभी देखें

* class [ColorBalanceAdjustmentLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* सभा [Aspose.PSD](../../../)


