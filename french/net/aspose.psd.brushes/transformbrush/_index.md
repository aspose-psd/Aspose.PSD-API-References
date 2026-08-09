---
title: "Classe TransformBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.TransformBrush. Un Brush avec des capacités de transformation"
type: docs
weight: 220
url: /fr/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

Un [`Brush`](../../aspose.psd/brush/) avec des capacités de transformation.

```csharp
public abstract class TransformBrush : Brush
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour assurer la compatibilité descendante avec GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtient ou définit une copie de [`Matrix`](../../aspose.psd/matrix/) qui définit une transformation géométrique locale pour ce `TransformBrush`. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtient ou définit une énumération [`WrapMode`](../../aspose.psd/wrapmode/) qui indique le mode d'habillage pour ce `TransformBrush`. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du [`Brush`](../../aspose.psd/brush/) actuel. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Multiplie la [`Matrix`](../../aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [`LinearGradientBrush`](../lineargradientbrush/) par la [`Matrix`](../../aspose.psd/matrix/) spécifiée en préfixant la [`Matrix`](../../aspose.psd/matrix/) spécifiée. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la [`Matrix`](../../aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [`LinearGradientBrush`](../lineargradientbrush/) par la [`Matrix`](../../aspose.psd/matrix/) spécifiée dans l'ordre indiqué. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Réinitialise la propriété [`Transform`](./transform/) à l'identité. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Redimensionne la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Redimensionne la transformation géométrique locale des valeurs spécifiées dans l'ordre indiqué. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Déplace la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |

### Voir aussi

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


