---
title: Class LayerState
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState classe. Les options de létat de la couche de ligne de temps.
type: docs
weight: 1860
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Les options de l'état de la couche de ligne de temps.

```csharp
public sealed class LayerState
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LayerState](layerstate/)(int) | Initialise une nouvelle instance du`LayerState` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Obtient ou définit le mode blen. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Obtient ou définit l'état activé. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Obtient ou définit la valeur d'opacité de remplissage. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Obtient ou définit la valeur HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Obtient ou définit l'id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Obtient ou définit le décalage de la position du calque par rapport à la position réelle du calque. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Obtient les effets d'état de calque. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Obtient ou définit la valeur VerticalFXRf. |

### Exemples

La classe TimeLine offre une capacité de haut niveau pour manipuler la chronologie de PsdImage, comme modifier le délai d'image ou modifier l'état du calque sur une image spécifique.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Changer la méthode de disposition de l'image 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Modification du délai de l'image 2
    timeLine.Frames[1].Delay = 15;

    // Modification de l'opacité du 'Calque 1' sur l'image 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // déplacer 'Calque 1' dans le coin inférieur gauche de l'image 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Ajoute un nouveau cadre
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Change blendMode de 'Calque 1' sur l'image 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Appliquer les modifications à l'instance PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* Assemblée [Aspose.PSD](../../)


