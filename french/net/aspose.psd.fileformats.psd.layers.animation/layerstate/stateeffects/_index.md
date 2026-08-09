---
title: "LayerState.StateEffects"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété LayerState. Obtient les effets d'état du calque"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
{{< psd/tize >}}
## LayerState.StateEffects property

Obtient les effets d'état du calque.

```csharp
public LayerStateEffects StateEffects { get; }
```

## Exemples

Le code suivant démontre la prise en charge des effets dans les cadres de la Timeline.

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

### Voir aussi

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


