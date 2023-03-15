---
title: LayerState.StateEffects
second_title: Aspose.PSD för .NET API-referens
description: LayerState fast egendom. Får lagertillståndseffekterna.
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Får lagertillståndseffekterna.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Exempel

Följande kod visar stöd för effekter i tidslinjeramar.

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

### Se även

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* hopsättning [Aspose.PSD](../../../)


