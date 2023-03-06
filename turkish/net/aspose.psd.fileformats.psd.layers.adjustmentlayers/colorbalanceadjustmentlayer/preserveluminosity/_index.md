---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD for .NET API Referansı
description: ColorBalanceAdjustmentLayer mülk. Bunun olup olmadığını gösteren bir değer alır veya ayarlar.BlncResource parlaklığı korur.
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) parlaklığı korur.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Mülk değeri

`doğru` parlaklığı koruyorsa; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki kod, ColorBalanceAdjustmentLayer için desteği gösterir.

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

### Ayrıca bakınız

* class [ColorBalanceAdjustmentLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* toplantı [Aspose.PSD](../../../)


