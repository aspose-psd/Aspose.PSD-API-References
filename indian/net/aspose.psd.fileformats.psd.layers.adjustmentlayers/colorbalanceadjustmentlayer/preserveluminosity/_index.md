---
title: "ColorBalanceAdjustmentLayer.PreserveLuminosity"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ColorBalanceAdjustmentLayer प्रॉपर्टी। प्राप्त करता है या सेट करता है वह मान जो दर्शाता है कि यह BlncResource चमक को संरक्षित करता है।"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

प्राप्त करता है या सेट करता है वह मान जो दर्शाता है कि यह [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) चमक को संरक्षित करता है।

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` यदि यह चमक को संरक्षित करता है; अन्यथा, `false`।

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


