---
title: "Classe PathMulticolorGradientBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.PathMulticolorGradientBrush. Encapsule un objet Brush avec un dégradé. Cette classe ne peut pas être héritée."
type: docs
weight: 190
url: /fr/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
{{< psd/tize >}}
## PathMulticolorGradientBrush class

Encapsule un objet [`Brush`](../../aspose.psd/brush/) avec un dégradé. Cette classe ne peut pas être héritée.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec le chemin spécifié. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec les points spécifiés. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec les points spécifiés. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec les points spécifiés et le mode d'habillage. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec les points spécifiés et le mode d'habillage. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Obtient ou définit le point central du dégradé de chemin. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Obtient ou définit le point de focalisation pour la chute du dégradé. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | Obtient ou définit un [`ColorBlend`](../../aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour assurer la compatibilité descendante avec GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Obtient les points du chemin sur lequel ce pinceau a été construit. |
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

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


