---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage-metod. Lägger till Vibrance-justeringslagret"
type: docs
weight: 490
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Lägger till Vibrance‑justeringslagret.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Returvärde

Ett nyss skapat Vibrance-lager.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


