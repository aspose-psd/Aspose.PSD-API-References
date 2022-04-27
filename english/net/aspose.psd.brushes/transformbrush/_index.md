---
title: TransformBrush
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 210
url: /net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

A [`Brush`](../../aspose.psd/brush) with transform capabilities.

```csharp
public abstract class TransformBrush : Brush
```

## Properties

| Name | Description |
| --- | --- |
| [IsTransformChanged](istransformchanged) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Transform](transform) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.psd/matrix) that defines a local geometric transform for this [`TransformBrush`](../transformbrush). |
| [WrapMode](wrapmode) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.psd/wrapmode) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush). |

## Methods

| Name | Description |
| --- | --- |
| [MultiplyTransform](multiplytransform)(Matrix) | Multiplies the [`Matrix`](../../aspose.psd/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.psd/matrix) by prepending the specified [`Matrix`](../../aspose.psd/matrix). |
| [MultiplyTransform](multiplytransform)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.psd/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.psd/matrix) in the specified order. |
| [ResetTransform](resettransform)() | Resets the [`Transform`](./transform) property to identity. |
| [RotateTransform](rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](rotatetransform)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](scaletransform)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](translatetransform)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* class [Brush](../../aspose.psd/brush)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->