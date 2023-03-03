---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ColorBalanceAdjustmentLayer संपत्त. एक मन प्रप्त करत है य सेट करत है ज दर्शत है क यहBlncResource चमक बरकरर रखत है.
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) चमक बरकरार रखता है.

```csharp
public bool PreserveLuminosity { get; set; }
```

### संपत्ति मूल्य

`सत्य` अगर यह चमक बरकरार रखता है; अन्यथा,`असत्य` .

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


