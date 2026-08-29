---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TimeLine. Applique les valeurs actuelles de la timeline à l'entrée PsdImage"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Applique les valeurs actuelles de la timeline à l'entrée [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| psdImage | PsdImage | L'image psd. |

## Exemples

La classe TimeLine offre une capacité de haut niveau pour manipuler la chronologie de PsdImage, comme changer le délai d'une frame ou modifier l'état d'un calque sur une frame spécifique.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Modifier la méthode de libération du cadre 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Modifier le délai du cadre 2
    timeLine.Frames[1].Delay = 15;

    // Modifier l'opacité de 'Layer 1' sur le cadre 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // Déplacer 'Layer 1' vers le coin inférieur gauche sur le cadre 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Ajoute un nouveau cadre
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Modifier le blendMode de 'Layer 1' sur la trame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Appliquer les modifications à l'instance PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Voir aussi

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


