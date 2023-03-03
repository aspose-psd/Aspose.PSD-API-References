---
title: Class Frame
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame classe. Les options de lélément de cadre chronologique.
type: docs
weight: 1840
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Les options de l'élément de cadre chronologique.

```csharp
public sealed class Frame
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Frame](frame/)(TimeLine) | Initialise une nouvelle instance du`Frame` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Obtient ou définit la valeur du délai de trame en centa-secondes. Par exemple, dans 1 seconde contient 100 centa-secondes. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Obtient ou définit la méthode de suppression du cadre. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Obtient ou définit l'ID de cadre. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Obtient ou définit les états de calque du cadre. |

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


