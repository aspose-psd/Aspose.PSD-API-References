---
title: Class LinearGradientBrush
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Brushes.LinearGradientBrush klas. Kapselt aBrush mit linearem Verlauf. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 140
url: /de/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Kapselt a[`Brush`](../../aspose.psd/brush/) mit linearem Verlauf. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich in (0,0) mit der Größe (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Initialisiert eine neue Instanz von`LinearGradientBrush` Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Ruft den Steigungswinkel ab oder legt ihn fest. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Holt oder setzt a[`Blend`](../../aspose.psd/blend/) die Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Ruft die Endverlaufsfarbe ab oder legt sie fest. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob die Gammakorrektur dafür aktiviert ist[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob[`Angle`](../lineargradientbrushbase/angle/) wird bei Transformationen damit verändert[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel Setzen der Transformationsmatrix oder Aufrufen einer der Methoden, die die Transformationsmatrix ändern. Die Eigenschaft wird aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass der Pinsel vollständig sichtbar ist, der Wert 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Ruft einen rechteckigen Bereich ab oder legt diesen fest, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Ruft die Anfangsverlaufsfarbe ab oder legt sie fest. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Ruft eine Kopie ab oder legt sie fest[`Matrix`](../../aspose.psd/matrix/) die dafür eine lokale geometrische Transformation definiert[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Holt oder setzt a[`WrapMode`](../../aspose.psd/wrapmode/) Enumeration, die den Umbruchmodus dafür angibt[`TransformBrush`](../transformbrush/) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen tiefen Klon des aktuellen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multipliziert die[`Matrix`](../../aspose.psd/matrix/) das die lokale geometrische Transformation davon darstellt`LinearGradientBrush` durch die angegebenen[`Matrix`](../../aspose.psd/matrix/) durch Voranstellen der angegebenen[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multipliziert die[`Matrix`](../../aspose.psd/matrix/) das die lokale geometrische Transformation davon darstellt`LinearGradientBrush` durch die angegebenen[`Matrix`](../../aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Setzt die zurück[`Transform`](../transformbrush/transform/) Eigentum an Identität. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge in der angegebenen Reihenfolge. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Erstellt einen linearen Farbverlauf mit einer Mittelfarbe und einem linearen Abfall zu einer einzigen Farbe an beiden Enden. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Erstellt einen linearen Farbverlauf mit einer Mittelfarbe und einem linearen Abfall zu einer einzigen Farbe an beiden Enden. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Erstellt einen Verlaufsabfall basierend auf einer glockenförmigen Kurve. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Erstellt einen Verlaufsabfall basierend auf einer glockenförmigen Kurve. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Siehe auch

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namensraum [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* Montage [Aspose.PSD](../../)


