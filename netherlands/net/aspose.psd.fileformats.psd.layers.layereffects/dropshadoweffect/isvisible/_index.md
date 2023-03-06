---
title: DropShadowEffect.IsVisible
second_title: Aspose.PSD voor .NET API-referentie
description: DropShadowEffect eigendom. Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is.

```csharp
public bool IsVisible { get; set; }
```

### Eigendoms-waarde

`WAAR` of deze instantie zichtbaar is; anders,`vals` .

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


