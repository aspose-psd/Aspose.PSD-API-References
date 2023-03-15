---
title: LayerState.StateEffects
second_title: Aspose.PSD voor .NET API-referentie
description: LayerState eigendom. Krijgt de laagstatuseffecten.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Krijgt de laagstatuseffecten.

```csharp
public LayerStateEffects StateEffects { get; }
```

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

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* montage [Aspose.PSD](../../../)


