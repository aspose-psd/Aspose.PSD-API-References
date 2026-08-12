---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD för .NET API‑referens"
description: "VibranceLayer-egenskap. Hämtar eller anger vibransen"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Hämtar eller anger vibransen.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Vibransen.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Vibrans måste vara i intervallet från -180 till +180 |

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


