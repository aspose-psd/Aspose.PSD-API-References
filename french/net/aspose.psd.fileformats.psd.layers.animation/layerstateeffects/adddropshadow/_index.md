---
title: LayerStateEffects.AddDropShadow
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerStateEffects méthode. Ajoute leffet dombre portée.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
## LayerStateEffects.AddDropShadow method

Ajoute l'effet d'ombre portée.

```csharp
public DropShadowEffect AddDropShadow()
```

### Return_Value

La nouvelle instance de[`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) classe.

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Assemblée [Aspose.PSD](../../../)


