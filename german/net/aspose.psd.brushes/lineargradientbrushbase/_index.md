---
title: "Klasse LinearGradientBrushBase"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.LinearGradientBrushBase Klasse. Stellt einen Brush mit Gradient-Fähigkeiten und entsprechenden Eigenschaften dar."
type: docs
weight: 150
url: /de/net/aspose.psd.brushes/lineargradientbrushbase/
---
{{< psd/tize >}}
## LinearGradientBrushBase class

Stellt einen [`Brush`](../../aspose.psd/brush/) mit Gradient-Fähigkeiten und entsprechenden Eigenschaften dar.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Liest oder setzt den Winkel des Farbverlaufs. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für diesen `LinearGradientBrushBase` aktiviert ist. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [`Angle`](./angle/) während Transformationen mit diesem `LinearGradientBrushBase` geändert wird. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Liest oder setzt einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
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


