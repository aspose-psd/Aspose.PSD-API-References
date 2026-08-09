---
title: "LayerStateEffects.AddGradientOverlay"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerStateEffects. Ajoute l'effet de superposition de dégradé"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddGradientOverlay method

Ajoute l'effet de superposition de dégradé.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Valeur de retour

La nouvelle instance de la classe [`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/).

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

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


