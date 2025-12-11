---
title: Class Graphics
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Graphics class. Represents the graphics according to the graphics engine used in the current assembly
type: docs
weight: 4740
url: /net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Represents the graphics according to the graphics engine used in the current assembly.

```csharp
public sealed class Graphics
```

## Constructors

| Name | Description |
| --- | --- |
| [Graphics](graphics/)(Image) | Initializes a new instance of the `Graphics` class. |

## Properties

| Name | Description |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Gets or sets the clip region. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Gets or sets the compositing quality. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Gets the horizontal resolution of this Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Gets the vertical resolution of this Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Gets the image. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Gets or sets the interpolation mode. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Gets a value indicating whether graphics is in BeginUpdate call state. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Gets or sets the scaling between world units and page units for this Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Gets or sets the unit of measure used for page coordinates in this Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Gets or sets image options, used to create paintable vactor images to draw. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Gets or sets the smoothing mode. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Gets or sets the text rendering hint. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Gets or sets a copy of the geometric world transformation for this `Graphics`. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Clears the graphics surface using the specified color. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Draws an arc representing a portion of an ellipse specified by a [`Rectangle`](../rectangle/) structure. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Draws an arc representing a portion of an ellipse specified by a [`RectangleF`](../rectanglef/) structure. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Draws a Bézier spline defined by four [`Point`](../point/) structures. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Draws a Bézier spline defined by four [`PointF`](../pointf/) structures. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Draws a series of Bézier splines from an array of [`PointF`](../pointf/) structures. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Draws a series of Bézier splines from an array of [`Point`](../point/) structures. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf/) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Draws a closed cardinal spline defined by an array of [`Point`](../point/) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf/) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Draws a closed cardinal spline defined by an array of [`Point`](../point/) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Draws a cardinal spline through a specified array of [`PointF`](../pointf/) structures. This method uses a default tension of 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Draws a cardinal spline through a specified array of [`Point`](../point/) structures. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf/) structures using a specified tension. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Draws a cardinal spline through a specified array of [`Point`](../point/) structures using a specified tension. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Draws a cardinal spline through a specified array of [`PointF`](../pointf/) structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Draws a cardinal spline through a specified array of [`Point`](../point/) structures using a specified tension. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Draws an ellipse specified by a bounding [`Rectangle`](../rectangle/) structure. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Draws an ellipse defined by a bounding [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Draws the specified [`Image`](./image/), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Draws the specified [`Image`](./image/), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Draws the specified [`Image`](./image/), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image/) at the specified location and with the specified size. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Draws a line connecting two [`Point`](../point/) structures. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Draws a line connecting two [`PointF`](../pointf/) structures. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Draws a series of line segments that connect an array of [`PointF`](../pointf/) structures. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Draws a series of line segments that connect an array of [`Point`](../point/) structures. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Draws a [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Draws a pie shape defined by an ellipse specified by a [`Rectangle`](../rectangle/) structure and two radial lines. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Draws a pie shape defined by an ellipse specified by a [`RectangleF`](../rectanglef/) structure and two radial lines. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Draws a polygon defined by an array of [`PointF`](../pointf/) structures. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Draws a polygon defined by an array of [`Point`](../point/) structures. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Draws a rectangle specified by a [`Rectangle`](../rectangle/) structure. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Draws a rectangle specified by a [`RectangleF`](../rectanglef/) structure. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Draws a series of rectangles specified by [`RectangleF`](../rectanglef/) structures. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Draws a series of rectangles specified by [`Rectangle`](../rectangle/) structures. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Draws the specified text string at the specified location with the specified [`Brush`](../brush/) and [`Font`](../font/) objects. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush/) and [`Font`](../font/) objects. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Draws the specified text string at the specified location with the specified [`Brush`](../brush/) and [`Font`](../font/) objects. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush/) and [`Font`](../font/) objects using the formatting attributes of the specified [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush/) and [`Font`](../font/) objects using the formatting attributes of the specified [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush/) and [`Font`](../font/) objects using the formatting attributes of the specified [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf/) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point/) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf/) structures using the specified fill mode and tension. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point/) structures using the specified fill mode and tension. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`Rectangle`](../rectangle/) structure. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`RectangleF`](../rectanglef/) structure. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Fills the interior of a [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef/) structure and two radial lines. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef/) structure and two radial lines. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf/) structures and Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point/) structures and Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf/) structures using the specified fill mode. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point/) structures using the specified fill mode. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Fills the interior of a rectangle specified by a [`Rectangle`](../rectangle/) structure. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Fills the interior of a rectangle specified by a [`RectangleF`](../rectanglef/) structure. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Fills the interiors of a series of rectangles specified by [`RectangleF`](../rectanglef/) structures. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Fills the interiors of a series of rectangles specified by [`Rectangle`](../rectangle/) structures. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Fills the interior of a [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplies the [`Matrix`](../matrix/) that represents the local geometric transform of this `Graphics` by the specified [`Matrix`](../matrix/) by prepending the specified [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../matrix/) that represents the local geometric transform of this `Graphics` by the specified [`Matrix`](../matrix/) in the specified order. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Resets the [`Transform`](./transform/) property to identity. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

## Examples

This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PSD format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class then export it to PSD file format.

```csharp
[C#]

//Create an instance of Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Draw an Arc by specifying the Pen object having Black color, 
    //a Rectangle surrounding the Arc, Start Angle and Sweep Angle
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Draw a Curve by specifying the Pen object having Green color and an array of Points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Draw an Ellipse using the Pen object and a surrounding Rectangle
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Draw a Line 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Draw a Pie segment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Draw a Polygon by specifying the Pen object having Red color and an array of Points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Draw a Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Create a SolidBrush object and set its various properties
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Draw a String using the SolidBrush object and Font, at specific Point
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Create an instance of PngOptions and set its various properties
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // save all changes.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


