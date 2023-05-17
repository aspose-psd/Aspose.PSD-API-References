---
title: Class LinearGradientBrushBase
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Brushes.LinearGradientBrushBase class. Represents a Brush with gradient capabilities and appropriate properties
type: docs
weight: 150
url: /net/aspose.psd.brushes/lineargradientbrushbase/
---
{{< psd/tize >}}
## LinearGradientBrushBase class

Represents a [`Brush`](../../aspose.psd/brush/) with gradient capabilities and appropriate properties.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Gets or sets the gradient angle. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Gets or sets a value indicating whether gamma correction is enabled for this `LinearGradientBrushBase`. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Gets or sets a value indicating whether [`Angle`](./angle/) is changed during trasnformations with this `LinearGradientBrushBase`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Gets or sets a rectangular region that defines the starting and ending points of the gradient. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.psd/matrix/) that defines a local geometric transform for this [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.psd/wrapmode/) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush/). |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplies the [`Matrix`](../../aspose.psd/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.psd/matrix/) by prepending the specified [`Matrix`](../../aspose.psd/matrix/). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.psd/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.psd/matrix/) in the specified order. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Resets the [`Transform`](../transformbrush/transform/) property to identity. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


