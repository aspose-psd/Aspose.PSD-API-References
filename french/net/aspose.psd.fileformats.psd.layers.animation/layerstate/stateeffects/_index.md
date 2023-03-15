---
title: LayerState.StateEffects
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerState propriété. Obtient les effets détat de calque.
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Obtient les effets d'état de calque.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Exemples

Le code suivant illustre la prise en charge des effets dans les images de la chronologie.

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

### Voir également

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* Assemblée [Aspose.PSD](../../../)


