---
title: Class TextureBrush
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Brushes.TextureBrush class. Each property of the TextureBrush class is a Brush object that uses an image to fill the interior of a shape. This class cannot be inherited
type: docs
weight: 210
url: /net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Each property of the `TextureBrush` class is a [`Brush`](../../aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructors

| Name | Description |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initializes a new instance of the `TextureBrush` class that uses the specified image. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initializes a new instance of the `TextureBrush` class that uses the specified image and bounding rectangle. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initializes a new instance of the `TextureBrush` class that uses the specified image and bounding rectangle. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initializes a new instance of the `TextureBrush` class that uses the specified image and wrap mode. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initializes a new instance of the `TextureBrush` class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initializes a new instance of the `TextureBrush` class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initializes a new instance of the `TextureBrush` class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initializes a new instance of the `TextureBrush` class that uses the specified image, wrap mode, and bounding rectangle. |

## Properties

| Name | Description |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Gets the [`Image`](../../aspose.psd/image/) object associated with this `TextureBrush` object. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Gets the [`ImageAttributes`](./imageattributes/) associated with this `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Gets the [`Rectangle`](../../aspose.psd/rectangle/) associated with this `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
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


