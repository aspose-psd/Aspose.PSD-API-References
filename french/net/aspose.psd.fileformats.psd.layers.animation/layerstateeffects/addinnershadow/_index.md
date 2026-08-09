---
title: "LayerStateEffects.AddInnerShadow"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "LayerStateEffects méthode. Ajoute l'effet d'ombre interne"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddInnerShadow method

Ajoute l'effet d'ombre interne.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### Valeur de retour

La nouvelle instance de la classe [`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/).

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

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


