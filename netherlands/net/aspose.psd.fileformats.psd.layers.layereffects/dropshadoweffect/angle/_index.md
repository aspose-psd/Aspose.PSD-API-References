---
title: DropShadowEffect.Angle
second_title: Aspose.PSD voor .NET API-referentie
description: DropShadowEffect eigendom. Haalt of stelt de hoek in graden in.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

Haalt of stelt de hoek in graden in.

```csharp
public int Angle { get; set; }
```

### Eigendoms-waarde

De hoek.

### Voorbeelden

De volgende code demonstreert het gebruik van de eigenschap Opacity van DropShadowEffect.

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

    // Voorbeeld met dekking = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Voorbeeld met dekking = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Zie ook

* class [DropShadowEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* montage [Aspose.PSD](../../../)


