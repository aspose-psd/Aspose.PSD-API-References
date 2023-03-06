---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD för .NET API-referens
description: VibranceLayer fast egendom. Får eller ställer in pulsen.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

Får eller ställer in pulsen.

```csharp
public int Vibrance { get; set; }
```

### Fastighetsvärde

Vibransen.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | Vibransen måste ligga inom området -180 till +180 |

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


