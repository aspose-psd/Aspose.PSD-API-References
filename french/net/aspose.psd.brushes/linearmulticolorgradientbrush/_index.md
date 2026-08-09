---
title: "Classe LinearMulticolorGradientBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.LinearMulticolorGradientBrush. Représente un Brush avec un dégradé linéaire défini par plusieurs couleurs et positions appropriées. Cette classe ne peut pas être héritée"
type: docs
weight: 160
url: /fr/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

Représente un [`Brush`](../../aspose.psd/brush/) avec un dégradé linéaire défini par plusieurs couleurs et positions appropriées. Cette classe ne peut pas être héritée.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les paramètres par défaut. La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtient ou définit l'angle du dégradé. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Obtient ou définit un [`ColorBlend`](../../aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtient ou définit une valeur indiquant si [`Angle`](../lineargradientbrushbase/angle/) est modifié pendant les transformations avec ce [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour assurer la compatibilité descendante avec GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtient ou définit une copie [`Matrix`](../../aspose.psd/matrix/) qui définit une transformation géométrique locale pour ce [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtient ou définit une énumération [`WrapMode`](../../aspose.psd/wrapmode/) qui indique le mode d'enveloppement pour ce [`TransformBrush`](../transformbrush/). |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du [`Brush`](../../aspose.psd/brush/) actuel. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplie la [`Matrix`](../../aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [`LinearGradientBrush`](../lineargradientbrush/) par la [`Matrix`](../../aspose.psd/matrix/) spécifiée en préfixant la [`Matrix`](../../aspose.psd/matrix/) spécifiée. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplie la [`Matrix`](../../aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [`LinearGradientBrush`](../lineargradientbrush/) par la [`Matrix`](../../aspose.psd/matrix/) spécifiée dans l'ordre indiqué. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Réinitialise la propriété [`Transform`](../transformbrush/transform/) à l'identité. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Redimensionne la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Redimensionne la transformation géométrique locale des valeurs spécifiées dans l'ordre indiqué. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Déplace la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |

### Voir aussi

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


