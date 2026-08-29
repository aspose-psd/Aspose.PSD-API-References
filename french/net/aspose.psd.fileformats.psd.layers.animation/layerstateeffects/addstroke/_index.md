---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerStateEffects. Ajoute l'effet de contour"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Ajoute l'effet de contour.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fillType | FillType | Le type remplissage de contour. |

### Valeur de retour

La nouvelle instance de la classe [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/).

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


