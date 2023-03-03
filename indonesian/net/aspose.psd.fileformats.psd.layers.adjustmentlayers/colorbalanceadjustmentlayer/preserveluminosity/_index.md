---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD untuk Referensi .NET API
description: ColorBalanceAdjustmentLayer Properti. Mendapat atau menetapkan nilai yang menunjukkan apakah iniBlncResource mempertahankan luminositas.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Mendapat atau menetapkan nilai yang menunjukkan apakah ini[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) mempertahankan luminositas.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Nilai properti

`BENAR` jika mempertahankan luminositas; jika tidak,`PALSU` .

### Contoh

Kode berikut menunjukkan dukungan untuk ColorBalanceAdjustmentLayer.

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

### Lihat juga

* class [ColorBalanceAdjustmentLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* perakitan [Aspose.PSD](../../../)


