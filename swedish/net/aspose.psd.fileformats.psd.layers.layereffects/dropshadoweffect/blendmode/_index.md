---
title: DropShadowEffect.BlendMode
second_title: Aspose.PSD för .NET API-referens
description: DropShadowEffect fast egendom. Hämtar eller ställer in blandningsläget.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
## DropShadowEffect.BlendMode property

Hämtar eller ställer in blandningsläget.

```csharp
public BlendMode BlendMode { get; set; }
```

### Fastighetsvärde

Blandningsläget.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* hopsättning [Aspose.PSD](../../../)


