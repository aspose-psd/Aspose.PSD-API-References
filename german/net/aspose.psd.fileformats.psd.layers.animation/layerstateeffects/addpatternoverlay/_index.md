---
title: LayerStateEffects.AddPatternOverlay
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerStateEffects methode. Fügt den Musterüberlagerungseffekt hinzu.
type: docs
weight: 80
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/
---
## LayerStateEffects.AddPatternOverlay method

Fügt den Musterüberlagerungseffekt hinzu.

```csharp
public PatternOverlayEffect AddPatternOverlay()
```

### Rückgabewert

Die neue Instanz der[`PatternOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) Klasse.

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

* class [PatternOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/)
* class [LayerStateEffects](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Montage [Aspose.PSD](../../../)


