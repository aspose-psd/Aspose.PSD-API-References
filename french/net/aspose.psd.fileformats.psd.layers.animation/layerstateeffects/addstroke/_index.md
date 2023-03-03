---
title: LayerStateEffects.AddStroke
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerStateEffects méthode. Ajoute leffet de trait.
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

Ajoute l'effet de trait.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fillType | FillType | Le remplissage de trait de type. |

### Return_Value

La nouvelle instance de[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) classe.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* Assemblée [Aspose.PSD](../../../)


