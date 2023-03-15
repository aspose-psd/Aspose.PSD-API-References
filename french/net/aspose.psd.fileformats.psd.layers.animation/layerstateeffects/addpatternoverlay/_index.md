---
title: LayerStateEffects.AddPatternOverlay
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerStateEffects méthode. Ajoute leffet de superposition de motifs.
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/
---
## LayerStateEffects.AddPatternOverlay method

Ajoute l'effet de superposition de motifs.

```csharp
public PatternOverlayEffect AddPatternOverlay()
```

### Return_Value

La nouvelle instance de[`PatternOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) classe.

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

* class [PatternOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/)
* class [LayerStateEffects](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Assemblée [Aspose.PSD](../../../)


