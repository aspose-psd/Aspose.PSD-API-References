---
title: LayerStateEffects.AddInnerShadow
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerStateEffects méthode. Ajoute leffet dombre intérieure.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
## LayerStateEffects.AddInnerShadow method

Ajoute l'effet d'ombre intérieure.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### Return_Value

La nouvelle instance de[`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) classe.

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

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Assemblée [Aspose.PSD](../../../)


