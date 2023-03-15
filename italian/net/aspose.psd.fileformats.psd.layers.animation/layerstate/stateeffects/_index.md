---
title: LayerState.StateEffects
second_title: Aspose.PSD per riferimento API .NET
description: LayerState proprietà. Ottiene gli effetti dello stato del livello.
type: docs
weight: 90
url: /it/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Ottiene gli effetti dello stato del livello.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Esempi

Il codice seguente illustra il supporto degli effetti nei fotogrammi della sequenza temporale.

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

### Guarda anche

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* assemblea [Aspose.PSD](../../../)


