---
title: "LayerStateEffects.AddColorOverlay"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerStateEffects-Methode. Fügt den Farbüberlagerungs-Effekt hinzu"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddColorOverlay method

Fügt den Farbüberlagerungseffekt hinzu.

```csharp
public ColorOverlayEffect AddColorOverlay()
```

### Rückgabewert

Die neue Instanz der [`ColorOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) Klasse.

## Beispiele

Der folgende Code demonstriert die Unterstützung von Effekten in Timeline-Frames.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### Siehe auch

* class [ColorOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


