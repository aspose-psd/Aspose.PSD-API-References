---
title: LayerStateEffects.AddGradientOverlay
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerStateEffects methode. Fügt den Verlaufsüberlagerungseffekt hinzu.
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
## LayerStateEffects.AddGradientOverlay method

Fügt den Verlaufsüberlagerungseffekt hinzu.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Rückgabewert

Die neue Instanz der[`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) Klasse.

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

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Montage [Aspose.PSD](../../../)


