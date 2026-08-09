---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerStateEffects-Methode. Fügt den Kontureffekt hinzu"
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Fügt den Kontur-Effekt hinzu.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillType | FillType | Der Typ Strichfüllung. |

### Rückgabewert

Die neue Instanz der [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) Klasse.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


