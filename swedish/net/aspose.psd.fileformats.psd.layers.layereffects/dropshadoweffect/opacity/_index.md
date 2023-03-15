---
title: DropShadowEffect.Opacity
second_title: Aspose.PSD för .NET API-referens
description: DropShadowEffect fast egendom. Hämtar eller ställer in opaciteten.
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/
---
## DropShadowEffect.Opacity property

Hämtar eller ställer in opaciteten.

```csharp
public byte Opacity { get; set; }
```

### Fastighetsvärde

Opaciteten.

### Exempel

Följande kod visar hur Opacity-egenskapen för DropShadowEffect används.

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

    // Exempel med Opacitet = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exempel med Opacitet = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Se även

* class [DropShadowEffect](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* hopsättning [Aspose.PSD](../../../)


