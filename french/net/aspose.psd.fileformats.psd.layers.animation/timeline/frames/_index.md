---
title: TimeLine.Frames
second_title: Référence de l'API Aspose.PSD pour .NET
description: TimeLine propriété. Obtient la liste des cadres.
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
## TimeLine.Frames property

Obtient la liste des cadres.

```csharp
public Frame[] Frames { get; set; }
```

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

* class [Frame](../../frame/)
* class [TimeLine](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* Assemblée [Aspose.PSD](../../../)


