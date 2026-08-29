---
title: "DropShadowEffect.Opacity"
second_title: "Aspose.PSD för .NET API‑referens"
description: "DropShadowEffect‑egenskap. Hämtar eller anger opaciteten"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/
---
{{< psd/tize >}}
## DropShadowEffect.Opacity property

Hämtar eller anger opaciteten.

```csharp
public byte Opacity { get; set; }
```

### Property Value

Opaciteten.

## Exempel

Följande kod demonstrerar användning av Opacity‑egenskapen för DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Exempel med Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exempel med Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Se även

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


