---
title: "Klasse LinearGradientBrush"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.LinearGradientBrush Klasse. Kapselt einen Brush mit einem linearen Farbverlauf. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 140
url: /de/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Kapselt einen [`Brush`](../../aspose.psd/brush/) mit einem linearen Farbverlauf. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse basierend auf einem Rechteck, den Start- und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse basierend auf einem Rechteck, den Start- und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse basierend auf einem Rechteck, den Start- und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Initialisiert eine neue Instanz der `LinearGradientBrush`-Klasse basierend auf einem Rechteck, den Start- und Endfarben sowie einem Orientierungswinkel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Liest oder setzt den Winkel des Farbverlaufs. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Liest oder setzt ein [`Blend`](../../aspose.psd/blend/), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Liest oder setzt die Endfarbe des Farbverlaufs. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für dieses [`LinearGradientBrushBase`](../lineargradientbrushbase/) aktiviert ist. |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Liest oder setzt ein [`ColorBlend`](../../aspose.psd/colorblend/), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [`Angle`](../lineargradientbrushbase/angle/) während Transformationen mit diesem [`LinearGradientBrushBase`](../lineargradientbrushbase/) geändert wird. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Liest oder setzt die Start- und Endfarben des Farbverlaufs. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Liest oder setzt einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Liest oder setzt die Startfarbe des Farbverlaufs. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Liest oder setzt eine Kopie von [`Matrix`](../../aspose.psd/matrix/), die eine lokale geometrische Transformation für diesen [`TransformBrush`](../transformbrush/) definiert. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Liest oder setzt eine [`WrapMode`](../../aspose.psd/wrapmode/)-Aufzählung, die den Wrap-Modus für diesen [`TransformBrush`](../transformbrush/) angibt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen Deep-Clone des aktuellen [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multipliziert die [`Matrix`](../../aspose.psd/matrix/), die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen [`Matrix`](../../aspose.psd/matrix/), indem die angegebene [`Matrix`](../../aspose.psd/matrix/) vorangestellt wird. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multipliziert die [`Matrix`](../../aspose.psd/matrix/), die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen [`Matrix`](../../aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Setzt die [`Transform`](../transformbrush/transform/)-Eigenschaft auf die Identität zurück. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation vor die Transformation. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode stellt die Skalierungs-Matrix vor die Transformation. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Erstellt einen linearen Farbverlauf mit einer Mittel-Farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Erstellt einen linearen Farbverlauf mit einer Mittel-Farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Erstellt einen Farbverlauf-Abfall basierend auf einer glockenförmigen Kurve. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Erstellt einen Farbverlauf-Abfall basierend auf einer glockenförmigen Kurve. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation am Anfang der Transformation ein. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Siehe auch

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


