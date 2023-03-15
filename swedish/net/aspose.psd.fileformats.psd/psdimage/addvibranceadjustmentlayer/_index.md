---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD för .NET API-referens
description: PsdImage metod. Lägger till vibrationsjusteringslagret.
type: docs
weight: 430
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Lägger till vibrationsjusteringslagret.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Returvärde

Ett nyskapat Vibrance-lager.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


