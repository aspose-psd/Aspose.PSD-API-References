---
title: LayerState.StateEffects
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerState eigendom. Ruft die Ebenenstatuseffekte ab.
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Ruft die Ebenenstatuseffekte ab.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung von Effekten in Timeline-Frames.

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

### Siehe auch

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* Montage [Aspose.PSD](../../../)


