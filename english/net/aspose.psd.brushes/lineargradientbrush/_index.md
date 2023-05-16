---
title: Class LinearGradientBrush
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Brushes.LinearGradientBrush class. Encapsulates a Brush with a linear gradient. This class cannot be inherited
type: docs
weight: 140
url: /net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Encapsulates a [`Brush`](../../aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Constructors

| Name | Description |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Initializes a new instance of the `LinearGradientBrush` class with default parameters. The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Initializes a new instance of the `LinearGradientBrush` class with the specified points and colors. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Initializes a new instance of the `LinearGradientBrush` class with the specified points and colors. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Initializes a new instance of the `LinearGradientBrush` class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Initializes a new instance of the `LinearGradientBrush` class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Initializes a new instance of the `LinearGradientBrush` class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Initializes a new instance of the `LinearGradientBrush` class based on a rectangle, starting and ending colors, and an orientation angle. |

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Gets or sets the gradient angle. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Gets or sets a [`Blend`](../../aspose.psd/blend/) that specifies positions and factors that define a custom falloff for the gradient. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Gets or sets the ending gradient color. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Gets or sets a value indicating whether gamma correction is enabled for this [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Gets or sets a [`ColorBlend`](../../aspose.psd/colorblend/) that defines a multicolor linear gradient. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Gets or sets a value indicating whether [`Angle`](../lineargradientbrushbase/angle/) is changed during trasnformations with this [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Gets or sets the starting and ending colors of the gradient. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Gets or sets a rectangular region that defines the starting and ending points of the gradient. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Gets or sets the starting gradient color. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.psd/matrix/) that defines a local geometric transform for this [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.psd/wrapmode/) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush/). |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplies the [`Matrix`](../../aspose.psd/matrix/) that represents the local geometric transform of this `LinearGradientBrush` by the specified [`Matrix`](../../aspose.psd/matrix/) by prepending the specified [`Matrix`](../../aspose.psd/matrix/). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.psd/matrix/) that represents the local geometric transform of this `LinearGradientBrush` by the specified [`Matrix`](../../aspose.psd/matrix/) in the specified order. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Resets the [`Transform`](../transformbrush/transform/) property to identity. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Creates a gradient falloff based on a bell-shaped curve. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Creates a gradient falloff based on a bell-shaped curve. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


