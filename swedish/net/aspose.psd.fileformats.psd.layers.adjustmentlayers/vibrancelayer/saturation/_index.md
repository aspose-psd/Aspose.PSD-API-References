---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD för .NET API‑referens"
description: "VibranceLayer egenskap. Hämtar eller anger saturationen"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

Hämtar eller anger mättnaden.

```csharp
public int Saturation { get; set; }
```

### Property Value

Saturationen.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Mättnad måste vara i intervallet från -100 till +100 |

## Exempel

Följande kodexempel demonstrerar stöd för VibranceLayer-lagret och möjligheten att redigera denna justering.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


