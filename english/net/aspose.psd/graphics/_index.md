---
title: Graphics
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4110
url: /net/aspose.psd/graphics/
---
## Graphics class

Represents the graphics according to the graphics engine used in the current assembly.

```csharp
public sealed class Graphics
```

## Constructors

| Name | Description |
| --- | --- |
| [Graphics](graphics)(Image) | Initializes a new instance of the [`Graphics`](../graphics) class. |

## Properties

| Name | Description |
| --- | --- |
| [Clip](clip) { get; set; } | Gets or sets the clip region. |
| [CompositingQuality](compositingquality) { get; set; } | Gets or sets the compositing quality. |
| [DpiX](dpix) { get; } | Gets the horizontal resolution of this Aspose.PSD.Graphics. |
| [DpiY](dpiy) { get; } | Gets the vertical resolution of this Aspose.PSD.Graphics. |
| [Image](image) { get; } | Gets the image. |
| [InterpolationMode](interpolationmode) { get; set; } | Gets or sets the interpolation mode. |
| [IsInBeginUpdateCall](isinbeginupdatecall) { get; } | Gets a value indicating whether graphics is in BeginUpdate call state. |
| [PageScale](pagescale) { get; set; } | Gets or sets the scaling between world units and page units for this Aspose.PSD.Graphics. |
| [PageUnit](pageunit) { get; set; } | Gets or sets the unit of measure used for page coordinates in this Aspose.PSD.Graphics. |
| [SmoothingMode](smoothingmode) { get; set; } | Gets or sets the smoothing mode. |
| [TextRenderingHint](textrenderinghint) { get; set; } | Gets or sets the text rendering hint. |
| [Transform](transform) { get; set; } | Gets or sets a copy of the geometric world transformation for this [`Graphics`](../graphics). |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdate](beginupdate)() | Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once. |
| [Clear](clear)(Color) | Clears the graphics surface using the specified color. |
| [DrawArc](drawarc)(Pen, Rectangle, float, float) | Draws an arc representing a portion of an ellipse specified by a [`Rectangle`](../rectangle) structure. |
| [DrawArc](drawarc)(Pen, RectangleF, float, float) | Draws an arc representing a portion of an ellipse specified by a [`RectangleF`](../rectanglef) structure. |
| [DrawArc](drawarc)(Pen, float, float, float, float, float, float) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawArc](drawarc)(Pen, int, int, int, int, int, int) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawBezier](drawbezier)(Pen, Point, Point, Point, Point) | Draws a Bézier spline defined by four [`Point`](../point) structures. |
| [DrawBezier](drawbezier)(Pen, PointF, PointF, PointF, PointF) | Draws a Bézier spline defined by four [`PointF`](../pointf) structures. |
| [DrawBezier](drawbezier)(Pen, float, float, float, float, float, float, float, float) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [DrawBeziers](drawbeziers)(Pen, PointF[]) | Draws a series of Bézier splines from an array of [`PointF`](../pointf) structures. |
| [DrawBeziers](drawbeziers)(Pen, Point[]) | Draws a series of Bézier splines from an array of [`Point`](../point) structures. |
| [DrawClosedCurve](drawclosedcurve)(Pen, PointF[]) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](drawclosedcurve)(Pen, Point[]) | Draws a closed cardinal spline defined by an array of [`Point`](../point) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](drawclosedcurve)(Pen, PointF[], float) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawClosedCurve](drawclosedcurve)(Pen, Point[], float) | Draws a closed cardinal spline defined by an array of [`Point`](../point) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawCurve](drawcurve)(Pen, PointF[]) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5. |
| [DrawCurve](drawcurve)(Pen, Point[]) | Draws a cardinal spline through a specified array of [`Point`](../point) structures. |
| [DrawCurve](drawcurve)(Pen, PointF[], float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures using a specified tension. |
| [DrawCurve](drawcurve)(Pen, Point[], float) | Draws a cardinal spline through a specified array of [`Point`](../point) structures using a specified tension. |
| [DrawCurve](drawcurve)(Pen, PointF[], int, int) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5. |
| [DrawCurve](drawcurve)(Pen, PointF[], int, int, float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawCurve](drawcurve)(Pen, Point[], int, int, float) | Draws a cardinal spline through a specified array of [`Point`](../point) structures using a specified tension. |
| [DrawEllipse](drawellipse)(Pen, Rectangle) | Draws an ellipse specified by a bounding [`Rectangle`](../rectangle) structure. |
| [DrawEllipse](drawellipse)(Pen, RectangleF) | Draws an ellipse defined by a bounding [`RectangleF`](../rectanglef). |
| [DrawEllipse](drawellipse)(Pen, float, float, float, float) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawEllipse](drawellipse)(Pen, int, int, int, int) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawImage](drawimage)(Image, Point) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](drawimage)(Image, PointF) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](drawimage)(Image, PointF[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Point[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Rectangle) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, RectangleF) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, float, float) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](drawimage)(Image, int, int) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [DrawImage](drawimage)(Image, PointF[], RectangleF) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Point[], Rectangle) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, PointF[], RectangleF, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Point[], Rectangle, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Rectangle, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, RectangleF, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, float, float, float, float) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, int, int, int, int) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](drawimage)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImageUnscaled](drawimageunscaled)(Image, Point) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](drawimageunscaled)(Image, Rectangle) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](drawimageunscaled)(Image, int, int) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [DrawImageUnscaled](drawimageunscaled)(Image, int, int, int, int) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaledAndClipped](drawimageunscaledandclipped)(Image, Rectangle) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [DrawLine](drawline)(Pen, Point, Point) | Draws a line connecting two [`Point`](../point) structures. |
| [DrawLine](drawline)(Pen, PointF, PointF) | Draws a line connecting two [`PointF`](../pointf) structures. |
| [DrawLine](drawline)(Pen, float, float, float, float) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLine](drawline)(Pen, int, int, int, int) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLines](drawlines)(Pen, PointF[]) | Draws a series of line segments that connect an array of [`PointF`](../pointf) structures. |
| [DrawLines](drawlines)(Pen, Point[]) | Draws a series of line segments that connect an array of [`Point`](../point) structures. |
| [DrawPath](drawpath)(Pen, GraphicsPath) | Draws a [`GraphicsPath`](../graphicspath). |
| [DrawPie](drawpie)(Pen, Rectangle, float, float) | Draws a pie shape defined by an ellipse specified by a [`Rectangle`](../rectangle) structure and two radial lines. |
| [DrawPie](drawpie)(Pen, RectangleF, float, float) | Draws a pie shape defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [DrawPie](drawpie)(Pen, float, float, float, float, float, float) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPie](drawpie)(Pen, int, int, int, int, int, int) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPolygon](drawpolygon)(Pen, PointF[]) | Draws a polygon defined by an array of [`PointF`](../pointf) structures. |
| [DrawPolygon](drawpolygon)(Pen, Point[]) | Draws a polygon defined by an array of [`Point`](../point) structures. |
| [DrawRectangle](drawrectangle)(Pen, Rectangle) | Draws a rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [DrawRectangle](drawrectangle)(Pen, RectangleF) | Draws a rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [DrawRectangle](drawrectangle)(Pen, float, float, float, float) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangle](drawrectangle)(Pen, int, int, int, int) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangles](drawrectangles)(Pen, RectangleF[]) | Draws a series of rectangles specified by [`RectangleF`](../rectanglef) structures. |
| [DrawRectangles](drawrectangles)(Pen, Rectangle[]) | Draws a series of rectangles specified by [`Rectangle`](../rectangle) structures. |
| [DrawString](drawstring)(string, Font, Brush, PointF) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](drawstring)(string, Font, Brush, RectangleF) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](drawstring)(string, Font, Brush, float, float) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](drawstring)(string, Font, Brush, PointF, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [DrawString](drawstring)(string, Font, Brush, RectangleF, StringFormat) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [DrawString](drawstring)(string, Font, Brush, float, float, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [EndUpdate](endupdate)() | Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method. |
| [FillClosedCurve](fillclosedcurve)(Brush, PointF[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](fillclosedcurve)(Brush, Point[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](fillclosedcurve)(Brush, PointF[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](fillclosedcurve)(Brush, Point[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](fillclosedcurve)(Brush, PointF[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures using the specified fill mode and tension. |
| [FillClosedCurve](fillclosedcurve)(Brush, Point[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures using the specified fill mode and tension. |
| [FillEllipse](fillellipse)(Brush, Rectangle) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [FillEllipse](fillellipse)(Brush, RectangleF) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [FillEllipse](fillellipse)(Brush, float, float, float, float) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillEllipse](fillellipse)(Brush, int, int, int, int) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillPath](fillpath)(Brush, GraphicsPath) | Fills the interior of a [`GraphicsPath`](../graphicspath). |
| [FillPie](fillpie)(Brush, Rectangle, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [FillPie](fillpie)(Brush, RectangleF, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [FillPie](fillpie)(Brush, float, float, float, float, float, float) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPie](fillpie)(Brush, int, int, int, int, int, int) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPolygon](fillpolygon)(Brush, PointF[]) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf) structures and Alternate. |
| [FillPolygon](fillpolygon)(Brush, Point[]) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point) structures and Alternate. |
| [FillPolygon](fillpolygon)(Brush, PointF[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf) structures using the specified fill mode. |
| [FillPolygon](fillpolygon)(Brush, Point[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point) structures using the specified fill mode. |
| [FillRectangle](fillrectangle)(Brush, Rectangle) | Fills the interior of a rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [FillRectangle](fillrectangle)(Brush, RectangleF) | Fills the interior of a rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [FillRectangle](fillrectangle)(Brush, float, float, float, float) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangle](fillrectangle)(Brush, int, int, int, int) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangles](fillrectangles)(Brush, RectangleF[]) | Fills the interiors of a series of rectangles specified by [`RectangleF`](../rectanglef) structures. |
| [FillRectangles](fillrectangles)(Brush, Rectangle[]) | Fills the interiors of a series of rectangles specified by [`Rectangle`](../rectangle) structures. |
| [FillRegion](fillregion)(Brush, Region) | Fills the interior of a [`Region`](../region). |
| [MultiplyTransform](multiplytransform)(Matrix) | Multiplies the [`Matrix`](../matrix) that represents the local geometric transform of this [`Graphics`](../graphics) by the specified [`Matrix`](../matrix) by prepending the specified [`Matrix`](../matrix). |
| [MultiplyTransform](multiplytransform)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../matrix) that represents the local geometric transform of this [`Graphics`](../graphics) by the specified [`Matrix`](../matrix) in the specified order. |
| [ResetTransform](resettransform)() | Resets the [`Transform`](./transform) property to identity. |
| [RotateTransform](rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](rotatetransform)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](scaletransform)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](translatetransform)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->