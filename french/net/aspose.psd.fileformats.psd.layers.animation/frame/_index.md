---
title: "Classe Frame"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame. Les options de l'élément de trame de la ligne de temps"
type: docs
weight: 1940
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

Les options de l'élément de trame de la chronologie.

```csharp
public sealed class Frame
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Frame](frame/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Obtient ou définit la valeur du délai de trame en centi-secondes. Par exemple, 1 seconde contient 100 centi-secondes. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Obtient ou définit la méthode de disposition de la trame. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Obtient ou définit l'identifiant de la trame. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | Obtient ou définit les états de calque de la trame. |

## Exemples

La classe Timeline offre une capacité de haut niveau pour manipuler la chronologie du PsdImage, comme modifier le délai d'un cadre ou éditer l'état du calque sur un cadre spécifique.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Modifier la méthode de libération du cadre 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Modifier le délai du cadre 2
    timeline.Frames[1].Delay = 15;

    // Modifier l'opacité de 'Layer 1' sur le cadre 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // Déplacer 'Layer 1' vers le coin inférieur gauche sur le cadre 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Ajoute un nouveau cadre
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Modifier le blendMode de 'Layer 1' sur la trame 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Appliquer les modifications à l'instance PsdImage
    psdImage.Save(outputPsd);
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


