---
title: Enum FrameDisposalMethod
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod énumération. La méthode délimination des images spécifie sil faut supprimer limage actuelle avant dafficher limage suivante. Vous sélectionnez une méthode délimination pour les animations qui incluent la transparence de larrièreplan pour spécifier si limage actuelle sera visible à travers les zones transparentes de limage suivante.
type: docs
weight: 1850
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

La méthode d'élimination des images spécifie s'il faut supprimer l'image actuelle avant d'afficher l'image suivante. Vous sélectionnez une méthode d'élimination pour les animations qui incluent la transparence de l'arrière-plan pour spécifier si l'image actuelle sera visible à travers les zones transparentes de l'image suivante.

```csharp
public enum FrameDisposalMethod
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Automatic | `0` | Détermine automatiquement une méthode de suppression pour l'image actuelle, en supprimant l'image actuelle si l'image suivante contient une transparence de calque. Pour la plupart des animations, l'option Automatique (par défaut) donne les résultats souhaités. |
| DoNotDispose | `1` | Préserve l'image actuelle lorsque l'image suivante est ajoutée à l'affichage. L'image actuelle (et les images précédentes) peut apparaître à travers les zones transparentes de l'image suivante. |
| Dispose | `2` | Supprime l'image actuelle de l'affichage avant l'affichage de l'image suivante. Une seule image est affichée à la fois (et l'image actuelle n'apparaît pas à travers les zones transparentes de l'image suivante). |

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


