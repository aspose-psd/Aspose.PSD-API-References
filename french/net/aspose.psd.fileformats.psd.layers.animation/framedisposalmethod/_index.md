---
title: "Énumération FrameDisposalMethod"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod. La méthode de disposition de la trame indique s'il faut supprimer la trame actuelle avant d'afficher la trame suivante. Vous choisissez une méthode de disposition pour les animations incluant la transparence d'arrière-plan afin de spécifier si la trame actuelle sera visible à travers les zones transparentes de la trame suivante."
type: docs
weight: 1950
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

La méthode de suppression de trame indique s'il faut ou non supprimer la trame actuelle avant d'afficher la trame suivante. Vous choisissez une méthode de suppression pour les animations incluant la transparence d'arrière-plan afin de spécifier si la trame actuelle sera visible à travers les zones transparentes de la trame suivante.

```csharp
public enum FrameDisposalMethod
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Automatic | `0` | Détermine automatiquement une méthode de disposition pour la trame actuelle, en supprimant la trame actuelle si la trame suivante contient de la transparence de calque. Pour la plupart des animations, l'option Automatique (par défaut) donne les résultats souhaités. |
| DoNotDispose | `1` | Conserve la trame actuelle lorsque la trame suivante est ajoutée à l'affichage. La trame actuelle (et les trames précédentes) peut apparaître à travers les zones transparentes de la trame suivante. |
| Dispose | `2` | Supprime la trame actuelle de l'affichage avant que la trame suivante ne soit affichée. Une seule trame est affichée à la fois (et la trame actuelle n'apparaît pas à travers les zones transparentes de la trame suivante). |

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


