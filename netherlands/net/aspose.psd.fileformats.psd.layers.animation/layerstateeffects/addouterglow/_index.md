---
title: LayerStateEffects.AddOuterGlow
second_title: Aspose.PSD voor .NET API-referentie
description: LayerStateEffects methode. Voegt het buitenste gloedeffect toe.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
## LayerStateEffects.AddOuterGlow method

Voegt het buitenste gloedeffect toe.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Winstwaarde

Het nieuwe exemplaar van de[`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) klas.

### Voorbeelden

De volgende code demonstreert de ondersteuning van effecten in tijdlijnframes.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### Zie ook

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* montage [Aspose.PSD](../../../)


