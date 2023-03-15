---
title: VibranceLayer.Saturation
second_title: Aspose.PSD för .NET API-referens
description: VibranceLayer fast egendom. Hämtar eller ställer in mättnaden.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Hämtar eller ställer in mättnaden.

```csharp
public int Saturation { get; set; }
```

### Fastighetsvärde

Mättnaden.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | Mättnaden måste ligga inom området -100 till +100 |

### Exempel

Följande kodexempel visar stöd för lagret VibranceLayer och möjligheten att redigera denna justering.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Skapa ett nytt VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Se även

* class [VibranceLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* hopsättning [Aspose.PSD](../../../)


