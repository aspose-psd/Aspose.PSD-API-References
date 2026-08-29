---
title: "Classe LayerState"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState. Les options de l'état de calque de la ligne de temps"
type: docs
weight: 1960
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Les options de l'état du calque de la chronologie.

```csharp
public sealed class LayerState
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LayerState](layerstate/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Obtient ou définit le mode de fusion. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Obtient ou définit l'état activé. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Obtient ou définit la valeur d'opacité du remplissage. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Obtient ou définit la valeur HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Obtient ou définit l'identifiant du calque. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Obtient ou définit le décalage de position du calque par rapport à la position réelle du calque. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Obtient les effets d'état du calque. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Obtient ou définit la valeur VerticalFXRf. |

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


