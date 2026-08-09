---
title: "Klasse TextureBrush"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.TextureBrush Klasse. Jede Eigenschaft der TextureBrush‑Klasse ist ein Brush‑Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 210
url: /de/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Jede Eigenschaft der `TextureBrush`‑Klasse ist ein [`Brush`](../../aspose.psd/brush/)‑Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild verwendet. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild und den Wrap‑Modus verwendet. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initialisiert eine neue Instanz der `TextureBrush`‑Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Liest das [`Image`](../../aspose.psd/image/)‑Objekt, das mit diesem `TextureBrush`‑Objekt verknüpft ist. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Ruft die [`ImageAttributes`](./imageattributes/) ab, die mit diesem `TextureBrush` verknüpft ist. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Ruft das [`Rectangle`](../../aspose.psd/rectangle/) ab, das mit diesem `TextureBrush` verknüpft ist. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Liest oder setzt eine Kopie von [`Matrix`](../../aspose.psd/matrix/), die eine lokale geometrische Transformation für diesen [`TransformBrush`](../transformbrush/) definiert. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Liest oder setzt eine [`WrapMode`](../../aspose.psd/wrapmode/)-Aufzählung, die den Wrap-Modus für diesen [`TransformBrush`](../transformbrush/) angibt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen Deep-Clone des aktuellen [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multipliziert die [`Matrix`](../../aspose.psd/matrix/), die die lokale geometrische Transformation dieses [`LinearGradientBrush`](../lineargradientbrush/) darstellt, mit der angegebenen [`Matrix`](../../aspose.psd/matrix/), indem die angegebene [`Matrix`](../../aspose.psd/matrix/) vorangestellt wird. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multipliziert die [`Matrix`](../../aspose.psd/matrix/), die die lokale geometrische Transformation dieses [`LinearGradientBrush`](../lineargradientbrush/) darstellt, mit der angegebenen [`Matrix`](../../aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Setzt die [`Transform`](../transformbrush/transform/)-Eigenschaft auf die Identität zurück. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation vor die Transformation. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode stellt die Skalierungs-Matrix vor die Transformation. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation am Anfang der Transformation ein. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Siehe auch

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


