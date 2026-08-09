---
title: "Classe TextureBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.TextureBrush. Chaque propriété de la classe TextureBrush est un objet Brush qui utilise une image pour remplir l'intérieur d'une forme. Cette classe ne peut pas être héritée"
type: docs
weight: 210
url: /fr/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Chaque propriété de la classe `TextureBrush` est un objet [`Brush`](../../aspose.psd/brush/) qui utilise une image pour remplir l'intérieur d'une forme. Cette classe ne peut pas être héritée.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée et le mode d'habillage. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initialise une nouvelle instance de la classe `TextureBrush` qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Obtient l'objet [`Image`](../../aspose.psd/image/) associé à cet objet `TextureBrush`. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Obtient les [`ImageAttributes`](./imageattributes/) associés à ce `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Obtient le [`Rectangle`](../../aspose.psd/rectangle/) associé à ce `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour assurer la compatibilité descendante avec GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


