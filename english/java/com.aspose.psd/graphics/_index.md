---
title: Graphics
second_title: Aspose.PSD for Java API Reference
description: Represents the graphics according to the graphics engine used in the current assembly.
type: docs
weight: 49
url: /java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Represents the graphics according to the graphics engine used in the current assembly.
## Constructors

| Constructor | Description |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Initializes a new instance of the  Graphics  class. |
## Fields

| Field | Description |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Gets bold text style size coefficient |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Gets italic text style size coefficient |
## Methods

| Method | Description |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Applies the effect. |
| [beginUpdate()](#beginUpdate--) | Starts caching of the following graphics operations. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Clears the graphics surface using the specified color. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Draws an arc representing a portion of an ellipse specified by a  Rectangle  structure. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Draws an arc representing a portion of an ellipse specified by a  RectangleF  structure. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Draws a Bézier spline defined by four  Point  structures. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Draws a Bézier spline defined by four  PointF  structures. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Draws a series of Bézier splines from an array of  PointF  structures. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Draws a series of Bézier splines from an array of  Point  structures. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Draws a closed cardinal spline defined by an array of  PointF  structures. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Draws a closed cardinal spline defined by an array of  PointF  structures using a specified tension. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Draws a closed cardinal spline defined by an array of  Point  structures. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Draws a closed cardinal spline defined by an array of  Point  structures using a specified tension. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Draws a cardinal spline through a specified array of  PointF  structures. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Draws a cardinal spline through a specified array of  PointF  structures using a specified tension. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Draws a cardinal spline through a specified array of  PointF  structures. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Draws a cardinal spline through a specified array of  PointF  structures using a specified tension. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Draws a cardinal spline through a specified array of  Point  structures. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Draws a cardinal spline through a specified array of  Point  structures using a specified tension. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Draws a cardinal spline through a specified array of  Point  structures using a specified tension. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Draws an ellipse specified by a bounding  Rectangle  structure. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Draws an ellipse defined by a bounding  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Draws the specified  Image , using its original physical size, at the specified location. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Draws the specified  Image , using its original physical size, at the specified location. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Draws the specified portion of the specified  image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Draws the specified  Image , using its original physical size, at the specified location. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Draws the specified  Image  at the specified location and with the specified size. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Draws a line connecting two  Point  structures. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Draws a line connecting two  PointF  structures. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Draws a line connecting the two points specified by the coordinate pairs. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Draws a line connecting the two points specified by the coordinate pairs. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Draws a series of line segments that connect an array of  PointF  structures. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Draws a series of line segments that connect an array of  Point  structures. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Draws a  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Draws a pie shape defined by an ellipse specified by a  Rectangle  structure and two radial lines. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Draws a pie shape defined by an ellipse specified by a  RectangleF  structure and two radial lines. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Draws a polygon defined by an array of  PointF  structures. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Draws a polygon defined by an array of  Point  structures. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Draws a rectangle specified by a  Rectangle  structure. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Draws a rectangle specified by a  RectangleF  structure. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Draws a series of rectangles specified by  RectangleF  structures. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Draws a series of rectangles specified by  Rectangle  structures. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Draws the specified text string in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Draws the specified text string in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Draws the specified text string in Adobe-compatible way in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Draws the specified text string in Adobe-compatible way at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects. |
| [endUpdate()](#endUpdate--) | Finishes caching of the graphics operations started after BeginUpdate was called. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures using the specified fill mode. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures using the specified fill mode and tension. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures using the specified fill mode. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures using the specified fill mode and tension. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a  com.aspose.psd.Rectangle  structure. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a  com.aspose.psd.RectangleF  structure. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Fills the interior of a  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a  com.aspose.psd.RectangleF  structure and two radial lines. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a  com.aspose.psd.RectangleF  structure and two radial lines. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.PointF  structures and  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.PointF  structures using the specified fill mode. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.Point  structures and  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.Point  structures using the specified fill mode. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Fills the interior of a rectangle specified by a  Rectangle  structure. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Fills the interior of a rectangle specified by a  RectangleF  structure. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Fills the interiors of a series of rectangles specified by  RectangleF  structures. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Fills the interiors of a series of rectangles specified by  Rectangle  structures. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Fills the interior of a  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Gets or sets the clip region. |
| [getCompositingQuality()](#getCompositingQuality--) | Gets or sets the compositing quality. |
| [getDpiX()](#getDpiX--) | Gets the horizontal resolution of this com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Gets the vertical resolution of this com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Gets the image. |
| [getInterpolationMode()](#getInterpolationMode--) | Gets or sets the interpolation mode. |
| [getPageScale()](#getPageScale--) | Gets or sets the scaling between world units and page units for this com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Gets or sets the unit of measure used for page coordinates in this com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Gets or sets image options, used to create paintable vactor images to draw. |
| [getSmoothingMode()](#getSmoothingMode--) | Gets or sets the smoothing mode. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Gets or sets the text rendering hint. |
| [getTransform()](#getTransform--) | Gets or sets a copy of the geometric world transformation for this  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Gets a value indicating whether graphics is in BeginUpdate call state. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Measures the string using the [GraphicsPath](../../com.aspose.psd/graphicspath) class. |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Measures the string. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Measures the specified text string with specified parameters |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplies the  com.aspose.psd.Matrix  that represents the local geometric transform of this  com.aspose.psd.Graphics  by the specified  com.aspose.psd.Matrix  by prepending the specified  com.aspose.psd.matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplies the  com.aspose.psd.Matrix  that represents the local geometric transform of this  com.aspose.psd.Graphics  by the specified  com.aspose.psd.Matrix  in the specified order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Resets the  com.aspose.psd.graphics.Transform  property to identity. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Gets or sets the clip region. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Gets or sets the compositing quality. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Gets or sets the interpolation mode. |
| [setPageScale(float value)](#setPageScale-float-) | Gets or sets the scaling between world units and page units for this com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Gets or sets the unit of measure used for page coordinates in this com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Gets or sets image options, used to create paintable vactor images to draw. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Gets or sets the smoothing mode. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Gets or sets the text rendering hint. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Gets or sets a copy of the geometric world transformation for this  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Initializes a new instance of the  Graphics  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The source image. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Gets bold text style size coefficient

Using magic numbers since GDI always provides measurement only for Regular style.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Gets italic text style size coefficient

Using magic numbers since GDI always provides measurement only for Regular style.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Applies the effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| effect | com.aspose.internal.IEffect | The effect to apply. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once.

Note the effects after BeginUpdate is called will not be applied in case EndUpdate is not called.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Clears the graphics surface using the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | The color to clear the graphics surface by. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a  Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the arc. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  RectangleF  structure that defines the boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to ending point of the arc. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a  RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the arc. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  RectangleF  structure that defines the boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to ending point of the arc. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the arc. |
| x | float | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | float | Width of the rectangle that defines the ellipse. |
| height | float | Height of the rectangle that defines the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to ending point of the arc. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the arc. |
| x | int | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | int | Width of the rectangle that defines the ellipse. |
| height | int | Height of the rectangle that defines the ellipse. |
| startAngle | int | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | int | Angle in degrees measured clockwise from the  startAngle  parameter to ending point of the arc. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Draws a Bézier spline defined by four  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  structure that determines the color, width, and style of the curve. |
| pt1 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the starting point of the curve. |
| pt2 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the first control point for the curve. |
| pt3 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the second control point for the curve. |
| pt4 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the ending point of the curve. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Draws a Bézier spline defined by four  PointF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the curve. |
| pt1 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the starting point of the curve. |
| pt2 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the first control point for the curve. |
| pt3 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the second control point for the curve. |
| pt4 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the ending point of the curve. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the curve. |
| x1 | float | The x-coordinate of the starting point of the curve. |
| y1 | float | The y-coordinate of the starting point of the curve. |
| x2 | float | The x-coordinate of the first control point of the curve. |
| y2 | float | The y-coordinate of the first control point of the curve. |
| x3 | float | The x-coordinate of the second control point of the curve. |
| y3 | float | The y-coordinate of the second control point of the curve. |
| x4 | float | The x-coordinate of the ending point of the curve. |
| y4 | float | The y-coordinate of the ending point of the curve. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Draws a series of Bézier splines from an array of  PointF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that represent the points that determine the curve. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Draws a series of Bézier splines from an array of  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that represent the points that determine the curve. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Draws a closed cardinal spline defined by an array of  PointF  structures. This method uses a default tension of 0.5 and  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that define the spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Draws a closed cardinal spline defined by an array of  PointF  structures using a specified tension. This method uses a default  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Draws a closed cardinal spline defined by an array of  Point  structures. This method uses a default tension of 0.5 and  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that define the spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Draws a closed cardinal spline defined by an array of  Point  structures using a specified tension. This method uses a default  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Draws a cardinal spline through a specified array of  PointF  structures. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that define the spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Draws a cardinal spline through a specified array of  PointF  structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Draws a cardinal spline through a specified array of  PointF  structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that define the spline. |
| offset | int | Offset from the first element in the array of the  points  parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Draws a cardinal spline through a specified array of  PointF  structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that define the spline. |
| offset | int | Offset from the first element in the array of the  points  parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Draws a cardinal spline through a specified array of  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that define the spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Draws a cardinal spline through a specified array of  Point  structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Draws a cardinal spline through a specified array of  Point  structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that define the spline. |
| offset | int | Offset from the first element in the array of the  points  parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Draws an ellipse specified by a bounding  Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the ellipse. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  Rectangle  structure that defines the boundaries of the ellipse. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Draws an ellipse defined by a bounding  RectangleF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the ellipse. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  RectangleF  structure that defines the boundaries of the ellipse. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the ellipse. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the ellipse. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Draws the specified  Image , using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| point | [Point](../../com.aspose.psd/point) |  Point  structure that represents the location of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Draws the specified  Image , using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| point | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the upper-left corner of the drawn image. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | The source rectangle. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | The source rectangle. |
| srcUnit | int | The units of measure. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | The source rectangle. |
| srcUnit | int | The units of measure. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array of three PointF structures that define a parallelogram. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | The source rectangle. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | The source rectangle. |
| srcUnit | int | The units of measure. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Draws the specified portion of the specified  image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | The source rectangle. |
| srcUnit | int | The units of measure. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  Rectangle  structure that specifies the location and size of the drawn image. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | The rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | The rect destination. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | The rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | The rect destination. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  RectangleF  structure that specifies the location and size of the drawn image. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | The rect source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | The rect destination. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | The source rectangle. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | The destination rectangle. |
| graphicsUnit | int | The graphics unit to use. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes to use. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | The destination rectangle to draw in. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Draws the specified  Image , using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| width | float | Width of the drawn image. |
| height | float | Height of the drawn image. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Draws the specified image, using its original physical size, at the location specified by a coordinate pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Draws the specified  Image  at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | Width of the drawn image. |
| height | int | Height of the drawn image. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| point | [Point](../../com.aspose.psd/point) |  Point  structure that specifies the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  Rectangle  that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Draws the specified image using its original physical size at the location specified by a coordinate pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | The parameter is not used. |
| height | int | The parameter is not used. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  Rectangle  in which to draw the image. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Draws a line connecting two  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line. |
| point1 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the first point to connect. |
| point2 | [Point](../../com.aspose.psd/point) |  Point  structure that represents the second point to connect. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Draws a line connecting two  PointF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line. |
| point1 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the first point to connect. |
| point2 | [PointF](../../com.aspose.psd/pointf) |  PointF  structure that represents the second point to connect. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Draws a series of line segments that connect an array of  PointF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line segments. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that represent the points to connect. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Draws a series of line segments that connect an array of  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the line segments. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that represent the points to connect. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Draws a  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  com.aspose.psd.Pen  that determines the color, width, and style of the path. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) |  com.aspose.psd.GraphicsPath  to draw. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a  Rectangle  structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  Rectangle  structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the  startAngle  parameter to the second side of the pie shape. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a  RectangleF  structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  RectangleF  structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the  startAngle  parameter to the second side of the pie shape. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the pie shape. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the  startAngle  parameter to the second side of the pie shape. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the pie shape. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | int | Angle measured in degrees clockwise from the  startAngle  parameter to the second side of the pie shape. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Draws a polygon defined by an array of  PointF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the polygon. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures that represent the vertices of the polygon. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Draws a polygon defined by an array of  Point  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the polygon. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures that represent the vertices of the polygon. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Draws a rectangle specified by a  Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  Pen  that determines the color, width, and style of the rectangle. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | A  Rectangle  structure that represents the rectangle to draw. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Draws a rectangle specified by a  RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  Pen  that determines the color, width, and style of the rectangle. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | A  RectangleF  structure that represents the rectangle to draw. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  Pen  that determines the color, width, and style of the rectangle. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | float | The width of the rectangle to draw. |
| height | float | The height of the rectangle to draw. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the rectangle. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | Width of the rectangle to draw. |
| height | int | Height of the rectangle to draw. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Draws a series of rectangles specified by  RectangleF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the outlines of the rectangles. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array of  RectangleF  structures that represent the rectangles to draw. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Draws a series of rectangles specified by  Rectangle  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) |  Pen  that determines the color, width, and style of the outlines of the rectangles. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array of  Rectangle  structures that represent the rectangles to draw. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| point | [PointF](../../com.aspose.psd/pointf) |  com.aspose.psd.PointF  structure that specifies the upper-left corner of the drawn text. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| point | [PointF](../../com.aspose.psd/pointf) |  com.aspose.psd.PointF  structure that specifies the upper-left corner of the drawn text. |
| format | [StringFormat](../../com.aspose.psd/stringformat) |  com.aspose.psd.StringFormat  that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Draws the specified text string in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) |  com.aspose.psd.RectangleF  structure that specifies the location of the drawn text. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Draws the specified text string in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) |  com.aspose.psd.RectangleF  structure that specifies the location of the drawn text. |
| format | [StringFormat](../../com.aspose.psd/stringformat) |  com.aspose.psd.StringFormat  that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Draws the specified text string at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |
| format | [StringFormat](../../com.aspose.psd/stringformat) |  com.aspose.psd.StringFormat  that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Draws the specified text string in Adobe-compatible way in the specified rectangle with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects using the formatting attributes of the specified  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) |  com.aspose.psd.RectangleF  structure that specifies the location of the drawn text. |
| format | [StringFormat](../../com.aspose.psd/stringformat) |  com.aspose.psd.StringFormat  that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Draws the specified text string in Adobe-compatible way at the specified location with the specified  com.aspose.psd.Brush  and  com.aspose.psd.Font  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.psd/font) |  com.aspose.psd.Font  that defines the text format of the string. |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures. This method uses a default tension of 0.5 and  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  com.aspose.psd.PointF  structures that define the spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  com.aspose.psd.PointF  structures that define the spline. |
| fillmode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines how the curve is filled. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.PointF  structures using the specified fill mode and tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | A  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  com.aspose.psd.PointF  structures that define the spline. |
| fillmode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures. This method uses a default tension of 0.5 and  FillMode.Alternate  fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  com.aspose.psd.Point  structures that define the spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  com.aspose.psd.Point  structures that define the spline. |
| fillmode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines how the curve is filled. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Fills the interior of a closed cardinal spline curve defined by an array of  com.aspose.psd.Point  structures using the specified fill mode and tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  com.aspose.psd.Point  structures that define the spline. |
| fillmode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  com.aspose.psd.Rectangle  structure that represents the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  com.aspose.psd.RectangleF  structure that represents the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Fills the interior of a  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) |  com.aspose.psd.GraphicsPath  that represents the path to fill. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a  com.aspose.psd.RectangleF  structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  com.aspose.psd.Rectangle  structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to the second side of the pie section. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a  com.aspose.psd.RectangleF  structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  com.aspose.psd.RectangleF  structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to the second side of the pie section. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the  startAngle  parameter to the second side of the pie section. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | int | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | int | Angle in degrees measured clockwise from the  startAngle  parameter to the second side of the pie section. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.PointF  structures and  FillMode.Alternate .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  com.aspose.psd.PointF  structures that represent the vertices of the polygon to fill. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.PointF  structures using the specified fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  com.aspose.psd.PointF  structures that represent the vertices of the polygon to fill. |
| fillMode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines the style of the fill. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.Point  structures and  FillMode.Alternate .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  com.aspose.psd.Point  structures that represent the vertices of the polygon to fill. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Fills the interior of a polygon defined by an array of points specified by  com.aspose.psd.Point  structures using the specified fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  com.aspose.psd.Point  structures that represent the vertices of the polygon to fill. |
| fillMode | int | Member of the  com.aspose.psd.FillMode  enumeration that determines the style of the fill. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Fills the interior of a rectangle specified by a  Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  Rectangle  structure that represents the rectangle to fill. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Fills the interior of a rectangle specified by a  RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) |  RectangleF  structure that represents the rectangle to fill. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | float | Width of the rectangle to fill. |
| height | float | Height of the rectangle to fill. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | int | Width of the rectangle to fill. |
| height | int | Height of the rectangle to fill. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Fills the interiors of a series of rectangles specified by  RectangleF  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array of  Rectangle  structures that represent the rectangles to fill. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Fills the interiors of a series of rectangles specified by  Rectangle  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  Brush  that determines the characteristics of the fill. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array of  Rectangle  structures that represent the rectangles to fill. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Fills the interior of a  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) |  com.aspose.psd.Brush  that determines the characteristics of the fill. |
| region | [Region](../../com.aspose.psd/region) |  com.aspose.psd.Region  that represents the area to fill. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


Gets or sets the clip region.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Gets or sets the compositing quality.

**Returns:**
int - The compositing quality.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Gets the horizontal resolution of this com.aspose.psd.graphics.

**Returns:**
float - The value, in dots per inch, for the horizontal resolution supported by this com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Gets the vertical resolution of this com.aspose.psd.graphics.

**Returns:**
float - The value, in dots per inch, for the vertical resolution supported by this com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Gets the image.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Gets or sets the interpolation mode.

**Returns:**
int - The interpolation mode.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Gets or sets the scaling between world units and page units for this com.aspose.psd.graphics.

**Returns:**
float - The scaling between world units and page units for this com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Gets or sets the unit of measure used for page coordinates in this com.aspose.psd.graphics.

**Returns:**
int - The unit of measure used for page coordinates in this com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Gets or sets image options, used to create paintable vactor images to draw.

Value: The image options, used to create paintable vactor images to draw.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Gets or sets the smoothing mode.

**Returns:**
int - The smoothing mode.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Gets or sets the text rendering hint.

**Returns:**
int - The text rendering hint.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets or sets a copy of the geometric world transformation for this  com.aspose.psd.graphics .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Gets a value indicating whether graphics is in BeginUpdate call state.

**Returns:**
boolean -  True  if graphics is in BeginUpdate call state; otherwise,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Measures the string using the [GraphicsPath](../../com.aspose.psd/graphicspath) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | The font. |
| text | java.lang.String | The text. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Measures the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | The font. |
| text | java.lang.String | The text.

--------------------

GDI result is almost always not valid for Italic and often not valid for Bold styles. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Measures the specified text string with specified parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to measure. |
| font | [Font](../../com.aspose.psd/font) | The font to measure. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | The layout area. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | The string format. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | The get private font cache. |
| useMagicNumbersForStyles | boolean | if set to  true  [use magic numbers for styles]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the  com.aspose.psd.Matrix  that represents the local geometric transform of this  com.aspose.psd.Graphics  by the specified  com.aspose.psd.Matrix  by prepending the specified  com.aspose.psd.matrix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  com.aspose.psd.Matrix  by which to multiply the geometric transform. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the  com.aspose.psd.Matrix  that represents the local geometric transform of this  com.aspose.psd.Graphics  by the specified  com.aspose.psd.Matrix  in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  com.aspose.psd.Matrix  by which to multiply the geometric transform. |
| order | int | A  com.aspose.psd.MatrixOrder  that specifies in which order to multiply the two matrices. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets the  com.aspose.psd.graphics.Transform  property to identity.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |
| order | int | A  com.aspose.psd.MatrixOrder  that specifies whether to append or prepend the rotation matrix. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | int | A  com.aspose.psd.MatrixOrder  that specifies whether to append or prepend the scaling matrix. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Gets or sets the clip region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | The clip region. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Gets or sets the compositing quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The compositing quality. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Gets or sets the interpolation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The interpolation mode. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Gets or sets the scaling between world units and page units for this com.aspose.psd.graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The scaling between world units and page units for this com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Gets or sets the unit of measure used for page coordinates in this com.aspose.psd.graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The unit of measure used for page coordinates in this com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Gets or sets image options, used to create paintable vactor images to draw.

Value: The image options, used to create paintable vactor images to draw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Gets or sets the smoothing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The smoothing mode. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Gets or sets the text rendering hint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The text rendering hint. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Gets or sets a copy of the geometric world transformation for this  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | int | The order (prepend or append) in which to apply the translation. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

