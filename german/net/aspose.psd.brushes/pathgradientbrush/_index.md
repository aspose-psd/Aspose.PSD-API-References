---
title: "Klasse PathGradientBrush"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.PathGradientBrush Klasse. Kapselt ein Brush-Objekt mit einem Farbverlauf. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 170
url: /de/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Kapselt ein [`Brush`](../../aspose.psd/brush/)‑Objekt mit einem Verlauf. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Initialisiert eine neue Instanz der `PathGradientBrush`-Klasse mit dem angegebenen Pfad. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Initialisiert eine neue Instanz der `PathGradientBrush`-Klasse mit den angegebenen Punkten. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Initialisiert eine neue Instanz der `PathGradientBrush`-Klasse mit den angegebenen Punkten. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Initialisiert eine neue Instanz der `PathGradientBrush`-Klasse mit den angegebenen Punkten und dem Wrap-Modus. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Initialisiert eine neue Instanz der `PathGradientBrush`-Klasse mit den angegebenen Punkten und dem Wrap-Modus. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Liest oder setzt ein [`Blend`](../../aspose.psd/blend/), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Liest oder setzt die Farbe im Zentrum des Pfadverlaufs. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Liest oder setzt den Fokuspunkt für den Verlaufabfall. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Liest oder setzt ein [`ColorBlend`](../../aspose.psd/colorblend/), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Liest oder setzt ein Array von Farben, das den Punkten im Pfad entspricht, den dieser `PathGradientBrush` füllt. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Erstellt einen Farbverlauf mit einer Zentralfarbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Erstellt einen Farbverlauf mit einer Zentralfarbe und einem linearen Abfall zu jeder umgebenden Farbe. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation am Anfang der Transformation ein. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

## Hinweise

Die Zentralfarbe ist standardmäßig weiß. Ein Benutzer kann diesen Wert jederzeit später ändern.

Das Array der Umgebungsfarben wird standardmäßig mit einem einzelnen Element, das die weiße Farbe enthält, initialisiert. Die Umgebungsfarben können später geändert werden, jedoch ist mindestens ein einzelnes Element erforderlich, wenn die Umgebungsfarben festgelegt werden.

Siehe [`Blend`](./blend/) für weitere Details zur Initialisierung.

### Siehe auch

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


