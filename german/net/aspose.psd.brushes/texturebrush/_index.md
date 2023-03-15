---
title: Class TextureBrush
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Brushes.TextureBrush klas. Jede Eigenschaft derTextureBrush Klasse ist einBrush Objekt das ein Bild verwendet um das Innere einer Form zu füllen. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 210
url: /de/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Jede Eigenschaft der`TextureBrush` Klasse ist ein[`Brush`](../../aspose.psd/brush/) Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild verwendet. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild und den Umbruchmodus verwendet. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildattribute verwendet. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initialisiert eine neue Instanz von`TextureBrush` Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildattribute verwendet. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initialisiert eine neue Instanz von`TextureBrush`Klasse, die das angegebene Bild, den Umbruchmodus und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initialisiert eine neue Instanz von`TextureBrush`Klasse, die das angegebene Bild, den Umbruchmodus und das Begrenzungsrechteck verwendet. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Ruft die ab[`Image`](../../aspose.psd/image/) damit verbundenes Objekt`TextureBrush` Objekt. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Ruft die ab[`ImageAttributes`](./imageattributes/) damit verbunden`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Ruft die ab[`Rectangle`](../../aspose.psd/rectangle/) damit verbunden`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel Setzen der Transformationsmatrix oder Aufrufen einer der Methoden, die die Transformationsmatrix ändern. Die Eigenschaft wird aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass der Pinsel vollständig sichtbar ist, der Wert 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Ruft eine Kopie ab oder legt sie fest[`Matrix`](../../aspose.psd/matrix/) die dafür eine lokale geometrische Transformation definiert[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Holt oder setzt a[`WrapMode`](../../aspose.psd/wrapmode/) Enumeration, die den Umbruchmodus dafür angibt[`TransformBrush`](../transformbrush/) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen tiefen Klon des aktuellen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multipliziert die[`Matrix`](../../aspose.psd/matrix/) das die lokale geometrische Transformation davon darstellt[`LinearGradientBrush`](../lineargradientbrush/) durch die angegebenen[`Matrix`](../../aspose.psd/matrix/) durch Voranstellen der angegebenen[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multipliziert die[`Matrix`](../../aspose.psd/matrix/) das die lokale geometrische Transformation davon darstellt[`LinearGradientBrush`](../lineargradientbrush/) durch die angegebenen[`Matrix`](../../aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Setzt die zurück[`Transform`](../transformbrush/transform/) Eigentum an Identität. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge in der angegebenen Reihenfolge. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Siehe auch

* class [TransformBrush](../transformbrush/)
* namensraum [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* Montage [Aspose.PSD](../../)


