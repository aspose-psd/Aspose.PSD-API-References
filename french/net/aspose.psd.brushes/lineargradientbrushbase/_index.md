---
title: Class LinearGradientBrushBase
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Brushes.LinearGradientBrushBase classe. Représente unBrush avec des capacités de dégradé et des propriétés appropriées.
type: docs
weight: 150
url: /fr/net/aspose.psd.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

Représente un[`Brush`](../../aspose.psd/brush/) avec des capacités de dégradé et des propriétés appropriées.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtient ou définit l'angle du dégradé. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce`LinearGradientBrushBase` . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtient ou définit une valeur indiquant si[`Angle`](./angle/) est changé lors des transformations avec ceci`LinearGradientBrushBase` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la rétrocompatibilité avec GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtient ou définit une copie[`Matrix`](../../aspose.psd/matrix/) qui définit une transformée géométrique locale pour cette[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtient ou définit un[`WrapMode`](../../aspose.psd/wrapmode/) énumération qui indique le mode de bouclage pour cette[`TransformBrush`](../transformbrush/) . |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du courant[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplie le[`Matrix`](../../aspose.psd/matrix/) qui représente la transformée géométrique locale de ce[`LinearGradientBrush`](../lineargradientbrush/) par le spécifié[`Matrix`](../../aspose.psd/matrix/) en préfixant le spécifié[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplie le[`Matrix`](../../aspose.psd/matrix/) qui représente la transformée géométrique locale de ce[`LinearGradientBrush`](../lineargradientbrush/) par le spécifié[`Matrix`](../../aspose.psd/matrix/) dans l'ordre spécifié. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Réinitialise le[`Transform`](../transformbrush/transform/) propriété à l'identité. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Fait pivoter la transformation géométrique locale de la quantité spécifiée. Cette méthode ajoute la rotation à la transformation. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la quantité spécifiée dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées. Cette méthode ajoute la matrice de mise à l'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées dans l'ordre spécifié. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction au début de la transformation. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Voir également

* class [TransformBrush](../transformbrush/)
* espace de noms [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* Assemblée [Aspose.PSD](../../)


