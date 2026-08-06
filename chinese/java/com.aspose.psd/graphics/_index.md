---
title: "Graphics"
second_title: "Aspose.PSD 的 Java API 参考"
description: "根据当前程序集使用的图形引擎表示图形。"
type: docs
weight: 49
url: /zh/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

根据当前程序集使用的图形引擎表示图形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | 初始化 Graphics 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | 获取粗体文本样式大小系数 |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | 获取斜体文本样式大小系数 |
## Methods

| Method | 描述 |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | 应用该效果。 |
| [beginUpdate()](#beginUpdate--) | 开始缓存以下图形操作。 |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | 使用指定颜色清除图形表面。 |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | 绘制由 Rectangle 结构指定的椭圆的一部分弧线。 |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | 绘制由 RectangleF 结构指定的椭圆的一部分弧线。 |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | 绘制由一对坐标、宽度和高度指定的椭圆的一部分弧线。 |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | 绘制由一对坐标、宽度和高度指定的椭圆的一部分弧线。 |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | 绘制由四个 Point 结构定义的贝塞尔样条。 |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 绘制由四个 PointF 结构定义的贝塞尔样条。 |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | 绘制由四对有序坐标点定义的贝塞尔样条。 |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 从 PointF 结构数组绘制一系列贝塞尔样条。 |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | 从 Point 结构数组绘制一系列贝塞尔样条。 |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 绘制由 PointF 结构数组定义的闭合基数样条。 |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 绘制使用指定张力、由 PointF 结构数组定义的闭合基数样条。 |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | 绘制由 Point 结构数组定义的闭合基数样条。 |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 绘制使用指定张力、由 Point 结构数组定义的闭合基数样条。 |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 绘制通过指定的 PointF 结构数组的基数样条。 |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 在指定的  PointF  结构数组上绘制一条基数样条曲线，使用指定的张力。 |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | 绘制通过指定的 PointF 结构数组的基数样条。 |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | 在指定的  PointF  结构数组上绘制一条基数样条曲线，使用指定的张力。 |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | 在指定的  Point  结构数组上绘制一条基数样条曲线。 |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 在指定的  Point  结构数组上绘制一条基数样条曲线，使用指定的张力。 |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | 在指定的  Point  结构数组上绘制一条基数样条曲线，使用指定的张力。 |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | 绘制由边界  Rectangle  结构指定的椭圆。 |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | 绘制由边界  RectangleF  定义的椭圆。 |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | 在指定位置绘制指定的  Image ，使用其原始物理尺寸。 |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | 在指定位置绘制指定的  Image ，使用其原始物理尺寸。 |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  image  的指定部分。 |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | 在指定位置绘制指定的  Image ，使用其原始物理尺寸。 |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | 在由坐标对指定的位置绘制指定的 image，使用其原始物理尺寸。 |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | 在指定位置并使用指定尺寸绘制指定的  Image 。 |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | 在指定位置绘制指定的 image，使用其原始物理尺寸。 |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 在指定位置绘制指定的 image，使用其原始物理尺寸。 |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | 在由坐标对指定的位置绘制指定的 image，使用其原始物理尺寸。 |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | 在指定位置绘制指定的 image，使用其原始物理尺寸。 |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 绘制指定的 image，保持原始尺寸且如有必要进行裁剪，以适应指定的矩形。 |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | 绘制连接两个  Point  结构的直线。 |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 绘制连接两个  PointF  结构的直线。 |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | 绘制连接由坐标对指定的两点的直线。 |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | 绘制连接由坐标对指定的两点的直线。 |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 绘制一系列连接  PointF  结构数组的线段。 |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | 绘制一系列连接  Point  结构数组的线段。 |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | 绘制一个  com.aspose.psd.graphicsPath 。 |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | 绘制由  Rectangle  结构指定的椭圆和两条径向线定义的饼形。 |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | 绘制由  RectangleF  结构指定的椭圆和两条径向线定义的饼形。 |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | 绘制由坐标对、宽度、高度指定的椭圆和两条径向线定义的饼形。 |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | 绘制由坐标对、宽度、高度指定的椭圆和两条径向线定义的饼形。 |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 绘制由  PointF  结构数组定义的多边形。 |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | 绘制由  Point  结构数组定义的多边形。 |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | 绘制由  Rectangle  结构指定的矩形。 |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | 绘制由  RectangleF  结构指定的矩形。 |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | 绘制由  RectangleF  结构指定的一系列矩形。 |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | 绘制由  Rectangle  结构指定的一系列矩形。 |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | 在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。 |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | 在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。 |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | 在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。 |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | 在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。 |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | 在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。 |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | 在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。 |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | 以 Adobe 兼容方式在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。 |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | 以 Adobe 兼容方式在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。 |
| [endUpdate()](#endUpdate--) | 完成在调用 BeginUpdate 后启动的图形操作的缓存。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | 填充由一组  com.aspose.psd.PointF  结构定义的闭合基数样条曲线的内部。 |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | 使用指定的填充模式填充由一组  com.aspose.psd.PointF  结构定义的闭合基数样条曲线的内部。 |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | 使用指定的填充模式和张力填充由一组  com.aspose.psd.PointF  结构定义的闭合基数样条曲线的内部。 |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | 填充由一组  com.aspose.psd.Point  结构定义的闭合基数样条曲线的内部。 |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | 使用指定的填充模式填充由一组  com.aspose.psd.Point  结构定义的闭合基数样条曲线的内部。 |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | 使用指定的填充模式和张力填充由一组  com.aspose.psd.Point  结构定义的闭合基数样条曲线的内部。 |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | 填充由  com.aspose.psd.Rectangle  结构指定的边界矩形定义的椭圆的内部。 |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | 填充由  com.aspose.psd.RectangleF  结构指定的边界矩形定义的椭圆的内部。 |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | 填充  com.aspose.psd.graphicsPath  的内部。 |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | 填充由  com.aspose.psd.RectangleF  结构和两条径向线指定的椭圆定义的饼形区域的内部。 |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | 填充由  com.aspose.psd.RectangleF  结构和两条径向线指定的椭圆定义的饼形区域的内部。 |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼形区域的内部。 |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼形区域的内部。 |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | 填充由一组  com.aspose.psd.PointF  结构指定的点以及  FillMode.Alternate  定义的多边形的内部。 |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | 使用指定的填充模式填充由一组  com.aspose.psd.PointF  结构指定的点定义的多边形的内部。 |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | 使用由 com.aspose.psd.Point 结构指定的点数组以及 FillMode.Alternate，填充多边形的内部。 |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | 使用指定的填充模式，填充由 com.aspose.psd.Point 结构指定的点数组定义的多边形内部。 |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | 填充由 Rectangle 结构指定的矩形内部。 |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | 填充由 RectangleF 结构指定的矩形内部。 |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | 填充由一对坐标、宽度和高度指定的矩形内部。 |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | 填充由一对坐标、宽度和高度指定的矩形内部。 |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | 填充由 RectangleF 结构指定的一系列矩形的内部。 |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | 填充由 Rectangle 结构指定的一系列矩形的内部。 |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | 填充 com.aspose.psd.region 的内部。 |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | 获取或设置剪裁区域。 |
| [getCompositingQuality()](#getCompositingQuality--) | 获取或设置合成质量。 |
| [getDpiX()](#getDpiX--) | 获取此 com.aspose.psd.graphics 的水平分辨率。 |
| [getDpiY()](#getDpiY--) | 获取此 com.aspose.psd.graphics 的垂直分辨率。 |
| [getImage()](#getImage--) | 获取图像。 |
| [getInterpolationMode()](#getInterpolationMode--) | 获取或设置插值模式。 |
| [getPageScale()](#getPageScale--) | 获取或设置此 com.aspose.psd.graphics 的世界单位与页面单位之间的缩放比例。 |
| [getPageUnit()](#getPageUnit--) | 获取或设置此 com.aspose.psd.graphics 中页面坐标使用的计量单位。 |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | 获取或设置图像选项，用于创建可绘制的 vactor 图像。 |
| [getSmoothingMode()](#getSmoothingMode--) | 获取或设置平滑模式。 |
| [getTextRenderingHint()](#getTextRenderingHint--) | 获取或设置文本呈现提示。 |
| [getTransform()](#getTransform--) | 获取或设置此 com.aspose.psd.graphics 的几何世界变换的副本。 |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | 获取一个值，指示 graphics 是否处于 BeginUpdate 调用状态。 |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | 使用 [GraphicsPath](../../com.aspose.psd/graphicspath) 类测量字符串。 |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | 测量字符串。 |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | 使用指定的参数测量指定的文本字符串。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 将表示此 com.aspose.psd.Graphics 的局部几何变换的 com.aspose.psd.Matrix 与指定的 com.aspose.psd.Matrix 相乘，方法是预先添加指定的 com.aspose.psd.matrix。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 将表示此 com.aspose.psd.Graphics 的局部几何变换的 com.aspose.psd.Matrix 按指定顺序乘以指定的 com.aspose.psd.Matrix。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | 将 com.aspose.psd.graphics.Transform 属性重置为单位矩阵。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转本地几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的顺序，以指定的角度旋转本地几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的比例缩放本地几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的顺序，以指定的比例缩放本地几何变换。 |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | 获取或设置剪裁区域。 |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | 获取或设置合成质量。 |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | 获取或设置插值模式。 |
| [setPageScale(float value)](#setPageScale-float-) | 获取或设置此 com.aspose.psd.graphics 的世界单位与页面单位之间的缩放比例。 |
| [setPageUnit(int value)](#setPageUnit-int-) | 获取或设置此 com.aspose.psd.graphics 中页面坐标使用的计量单位。 |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | 获取或设置图像选项，用于创建可绘制的 vactor 图像。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 获取或设置平滑模式。 |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | 获取或设置文本呈现提示。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 获取或设置此 com.aspose.psd.graphics 的几何世界变换的副本。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移本地几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的顺序，以指定的尺寸平移本地几何变换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


初始化 Graphics 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 源图像。 |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


获取粗体文本样式大小系数

使用魔法数字，因为 GDI 仅为 Regular 样式提供测量。

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


获取斜体文本样式大小系数

使用魔法数字，因为 GDI 仅为 Regular 样式提供测量。

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


应用该效果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 效果 | com.aspose.internal.IEffect | 要应用的效果。 |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


开始缓存以下图形操作。随后应用的图形效果不会立即生效，而是等到 EndUpdate 时一次性应用所有效果。

注意，如果在调用 BeginUpdate 后未调用 EndUpdate，则这些效果将不会被应用。

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


使用指定颜色清除图形表面。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 用于清除图形表面的颜色。 |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


绘制由 Rectangle 结构指定的椭圆的一部分弧线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，用于确定弧线的颜色、宽度和样式。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | RectangleF 结构，定义椭圆的边界。 |
| 起始角度 | float | 以度为单位的角度，顺时针从 x 轴测量到弧线的起始点。 |
| 扫掠角度 | float | 以度为单位的角度，顺时针从 startAngle 参数测量到弧线的结束点。 |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


绘制由 RectangleF 结构指定的椭圆的一部分弧线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，用于确定弧线的颜色、宽度和样式。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF 结构，定义椭圆的边界。 |
| 起始角度 | float | 以度为单位的角度，顺时针从 x 轴测量到弧线的起始点。 |
| 扫掠角度 | float | 以度为单位的角度，顺时针从 startAngle 参数测量到弧线的结束点。 |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


绘制由一对坐标、宽度和高度指定的椭圆的一部分弧线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，用于确定弧线的颜色、宽度和样式。 |
| x | float | 定义椭圆的矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的矩形左上角的 y 坐标。 |
| 宽度 | float | 定义椭圆的矩形的宽度。 |
| 高度 | float | 定义椭圆的矩形的高度。 |
| 起始角度 | float | 以度为单位的角度，顺时针从 x 轴测量到弧线的起始点。 |
| 扫掠角度 | float | 以度为单位的角度，顺时针从 startAngle 参数测量到弧线的结束点。 |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


绘制由一对坐标、宽度和高度指定的椭圆的一部分弧线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，用于确定弧线的颜色、宽度和样式。 |
| x | int | 定义椭圆的矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的矩形左上角的 y 坐标。 |
| 宽度 | int | 定义椭圆的矩形的宽度。 |
| 高度 | int | 定义椭圆的矩形的高度。 |
| 起始角度 | int | 以度为单位的角度，顺时针从 x 轴测量到弧线的起始点。 |
| 扫掠角度 | int | 以度为单位的角度，顺时针从 startAngle 参数测量到弧线的结束点。 |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


绘制由四个 Point 结构定义的贝塞尔样条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen 结构，确定曲线的颜色、宽度和样式。 |
| pt1 | [Point](../../com.aspose.psd/point) | Point 结构，表示曲线的起始点。 |
| pt2 | [Point](../../com.aspose.psd/point) | Point 结构，表示曲线的第一个控制点。 |
| pt3 | [Point](../../com.aspose.psd/point) | Point 结构，表示曲线的第二个控制点。 |
| pt4 | [Point](../../com.aspose.psd/point) | Point 结构，表示曲线的结束点。 |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


绘制由四个 PointF 结构定义的贝塞尔样条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和样式的笔。 |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  表示曲线起始点的结构体。 |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  表示曲线第一个控制点的结构体。 |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  表示曲线第二个控制点的结构体。 |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  表示曲线结束点的结构体。 |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


绘制由四对有序坐标点定义的贝塞尔样条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和样式的笔。 |
| x1 | float | 曲线起始点的 x 坐标。 |
| y1 | float | 曲线起始点的 y 坐标。 |
| x2 | float | 曲线第一个控制点的 x 坐标。 |
| y2 | float | 曲线第一个控制点的 y 坐标。 |
| x3 | float | 曲线第二个控制点的 x 坐标。 |
| y3 | float | 曲线第二个控制点的 y 坐标。 |
| x4 | float | 曲线结束点的 x 坐标。 |
| y4 | float | 曲线结束点的 y 坐标。 |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


从 PointF 结构数组绘制一系列贝塞尔样条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和样式的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  structures 表示决定曲线的点的数组。 |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


从 Point 结构数组绘制一系列贝塞尔样条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和样式的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  structures 表示决定曲线的点的数组。 |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


绘制由 PointF 结构体数组定义的闭合基数样条。此方法使用默认张力 0.5 和 FillMode.Alternate 填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的  PointF  结构数组。 |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


使用指定的张力绘制由  PointF  结构数组 定义的闭合基数样条。此方法使用默认的  FillMode.Alternate  填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的  PointF  结构数组。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


绘制由  Point  结构数组定义的闭合基数样条。此方法使用默认张力 0.5 和  FillMode.Alternate  填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的  Point  结构数组。 |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


使用指定的张力绘制由  Point  结构数组 定义的闭合基数样条。此方法使用默认的  FillMode.Alternate  填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的  Point  结构数组。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


通过指定的  PointF  结构数组绘制基数样条。此方法使用默认张力 0.5。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的  PointF  结构数组。 |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


在指定的  PointF  结构数组上绘制一条基数样条曲线，使用指定的张力。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 表示定义曲线的点的  PointF  结构数组。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


通过指定的  PointF  结构数组绘制基数样条。绘制从数组起始位置偏移开始。此方法使用默认张力 0.5。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的  PointF  结构数组。 |
| offset | int | 从数组中  points  参数的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | int | 起始点之后包含在曲线中的段数。 |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


通过指定的  PointF  结构数组使用指定的张力绘制基数样条。绘制从数组起始位置偏移开始。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的  PointF  结构数组。 |
| offset | int | 从数组中  points  参数的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | int | 起始点之后包含在曲线中的段数。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


在指定的  Point  结构数组上绘制一条基数样条曲线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的  Point  结构数组。 |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


在指定的  Point  结构数组上绘制一条基数样条曲线，使用指定的张力。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的  Point  结构数组。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


在指定的  Point  结构数组上绘制一条基数样条曲线，使用指定的张力。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  确定曲线的颜色、宽度和高度的笔。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的  Point  结构数组。 |
| offset | int | 从数组中  points  参数的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | int | 起始点之后包含在曲线中的段数。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


绘制由边界  Rectangle  结构指定的椭圆。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定椭圆颜色、宽度和样式的 Pen。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 定义椭圆边界的 Rectangle 结构。 |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


绘制由边界  RectangleF  定义的椭圆。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定椭圆颜色、宽度和样式的 Pen。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF 结构，定义椭圆的边界。 |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定椭圆颜色、宽度和样式的 Pen。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | float | 定义椭圆的边界矩形的宽度。 |
| 高度 | float | 定义椭圆的边界矩形的高度。 |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定椭圆颜色、宽度和样式的 Pen。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | int | 定义椭圆的边界矩形的宽度。 |
| 高度 | int | 定义椭圆的边界矩形的高度。 |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


在指定位置绘制指定的  Image ，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| point | [Point](../../com.aspose.psd/point) | 表示绘制图像左上角位置的 Point 结构。 |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


在指定位置绘制指定的  Image ，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| point | [PointF](../../com.aspose.psd/pointf) | 表示绘制图像左上角的 PointF 结构。 |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构数组。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 源矩形。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 源矩形。 |
| srcUnit | int | 度量单位。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 源矩形。 |
| srcUnit | int | 度量单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 图像属性。 |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 定义平行四边形的三个 PointF 结构数组。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 源矩形。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 源矩形。 |
| srcUnit | int | 度量单位。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  image  的指定部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 定义平行四边形的三个 PointF 结构数组。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 源矩形。 |
| srcUnit | int | 度量单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 图像属性。 |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle 结构，指定绘制图像的位置和大小。 |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | 源矩形。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | 源矩形。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 图像属性。 |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 图像属性。 |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF 结构，指定绘制图像的位置和大小。 |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | 源矩形。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | 源矩形。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 目标矩形。 |
| graphicsUnit | int | 要使用的图形单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 要使用的图像属性。 |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 目标矩形。 |
| graphicsUnit | int | 图形单位。 |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 要绘制的目标矩形。 |
| graphicsUnit | int | 图形单位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 图像属性。 |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


在指定位置绘制指定的  Image ，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |
| 宽度 | float | 绘制图像的宽度。 |
| 高度 | float | 绘制图像的高度。 |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


在由坐标对指定的位置绘制指定的 image，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


在指定位置并使用指定尺寸绘制指定的  Image 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| 宽度 | int | 绘制图像的宽度。 |
| 高度 | int | 绘制图像的高度。 |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


在指定位置绘制指定的 image，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| point | [Point](../../com.aspose.psd/point) | Point 结构，指定绘制图像的左上角。 |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


在指定位置绘制指定的 image，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle，指定绘制图像的左上角。矩形的 X 和 Y 属性指定左上角。Width 和 Height 属性被忽略。 |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


在由坐标对指定的位置绘制指定的 image，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


在指定位置绘制指定的 image，使用其原始物理尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| 宽度 | int | 此参数未使用。 |
| 高度 | int | 此参数未使用。 |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


绘制指定的 image，保持原始尺寸且如有必要进行裁剪，以适应指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 要绘制的图像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 用于绘制图像的 Rectangle。 |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


绘制连接两个  Point  结构的直线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，确定线条的颜色、宽度和样式。 |
| point1 | [Point](../../com.aspose.psd/point) | Point 结构，表示要连接的第一个点。 |
| point2 | [Point](../../com.aspose.psd/point) | Point 结构，表示要连接的第二个点。 |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


绘制连接两个  PointF  结构的直线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，确定线条的颜色、宽度和样式。 |
| point1 | [PointF](../../com.aspose.psd/pointf) | 表示要连接的第一个点的 PointF 结构。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 表示要连接的第二个点的 PointF 结构。 |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


绘制连接由坐标对指定的两点的直线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，确定线条的颜色、宽度和样式。 |
| x1 | float | 第一个点的 x 坐标。 |
| y1 | float | 第一个点的 y 坐标。 |
| x2 | float | 第二个点的 x 坐标。 |
| y2 | float | 第二个点的 y 坐标。 |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


绘制连接由坐标对指定的两点的直线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen，确定线条的颜色、宽度和样式。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


绘制一系列连接  PointF  结构数组的线段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定线段颜色、宽度和样式的 Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 表示要连接的点的 PointF 结构数组。 |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


绘制一系列连接  Point  结构数组的线段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定线段颜色、宽度和样式的 Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 表示要连接的点的 Point 结构数组。 |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


绘制一个  com.aspose.psd.graphicsPath 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定路径颜色、宽度和样式的 com.aspose.psd.Pen。 |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 用于绘制的 com.aspose.psd.GraphicsPath。 |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


绘制由  Rectangle  结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定饼形颜色、宽度和样式的 Pen。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示定义饼形所在椭圆的外接矩形的 Rectangle 结构。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼形第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼形第二边的角度（度）。 |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


绘制由  RectangleF  结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定饼形颜色、宽度和样式的 Pen。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示定义饼形所在椭圆的外接矩形的 RectangleF 结构。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼形第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼形第二边的角度（度）。 |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


绘制由坐标对、宽度、高度指定的椭圆和两条径向线定义的饼形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定饼形颜色、宽度和样式的 Pen。 |
| x | float | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | float | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| 宽度 | float | 定义饼形所在椭圆的外接矩形的宽度。 |
| 高度 | float | 定义饼形所在椭圆的外接矩形的高度。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼形第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼形第二边的角度（度）。 |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


绘制由坐标对、宽度、高度指定的椭圆和两条径向线定义的饼形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定饼形颜色、宽度和样式的 Pen。 |
| x | int | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | int | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| 宽度 | int | 定义饼形所在椭圆的外接矩形的宽度。 |
| 高度 | int | 定义饼形所在椭圆的外接矩形的高度。 |
| 起始角度 | int | 从 x 轴顺时针测量到饼形第一边的角度（度）。 |
| 扫掠角度 | int | 从 startAngle 参数顺时针测量到饼形第二边的角度（度）。 |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


绘制由  PointF  结构数组定义的多边形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定多边形颜色、宽度和样式的 Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 表示多边形顶点的 PointF 结构数组。 |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


绘制由  Point  结构数组定义的多边形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定多边形颜色、宽度和样式的 Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 表示多边形顶点的 Point 结构数组。 |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


绘制由  Rectangle  结构指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形颜色、宽度和样式的 Pen。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示要绘制的矩形的 Rectangle 结构。 |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


绘制由  RectangleF  结构指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形颜色、宽度和样式的 Pen。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示要绘制的矩形的 RectangleF 结构。 |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形颜色、宽度和样式的 Pen。 |
| x | float | 要绘制的矩形左上角的 x 坐标。 |
| y | float | 要绘制的矩形左上角的 y 坐标。 |
| 宽度 | float | 要绘制的矩形的宽度。 |
| 高度 | float | 要绘制的矩形的高度。 |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形颜色、宽度和样式的 Pen。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| 宽度 | int | 要绘制的矩形的宽度。 |
| 高度 | int | 要绘制的矩形的高度。 |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


绘制由  RectangleF  结构指定的一系列矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形轮廓颜色、宽度和样式的 Pen。 |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | 表示要绘制的矩形的 RectangleF 结构数组。 |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


绘制由  Rectangle  结构指定的一系列矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 确定矩形轮廓颜色、宽度和样式的 Pen。 |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 表示要绘制的矩形的 Rectangle 结构数组。 |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| point | [PointF](../../com.aspose.psd/pointf) | 指定已绘制文本左上角的 com.aspose.psd.PointF 结构。 |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| point | [PointF](../../com.aspose.psd/pointf) | 指定已绘制文本左上角的 com.aspose.psd.PointF 结构。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 指定应用于已绘制文本的格式属性（如行间距和对齐方式）的 com.aspose.psd.StringFormat。 |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 指定已绘制文本位置的 com.aspose.psd.RectangleF 结构。 |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 指定已绘制文本位置的 com.aspose.psd.RectangleF 结构。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 指定应用于已绘制文本的格式属性（如行间距和对齐方式）的 com.aspose.psd.StringFormat。 |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| x | float | 已绘制文本左上角的 x 坐标。 |
| y | float | 已绘制文本左上角的 y 坐标。 |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| x | float | 已绘制文本左上角的 x 坐标。 |
| y | float | 已绘制文本左上角的 y 坐标。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 指定应用于已绘制文本的格式属性（如行间距和对齐方式）的 com.aspose.psd.StringFormat。 |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


以 Adobe 兼容方式在指定的矩形内使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象，并使用指定的  com.aspose.psd.stringFormat  的格式属性绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 指定已绘制文本位置的 com.aspose.psd.RectangleF 结构。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 指定应用于已绘制文本的格式属性（如行间距和对齐方式）的 com.aspose.psd.StringFormat。 |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


以 Adobe 兼容方式在指定位置使用指定的  com.aspose.psd.Brush  和  com.aspose.psd.Font  对象绘制指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| s | java.lang.String | 要绘制的字符串。 |
| font | [Font](../../com.aspose.psd/font) | 定义字符串文本格式的 com.aspose.psd.Font。 |
| brush | [Brush](../../com.aspose.psd/brush) | 确定已绘制文本颜色和纹理的 com.aspose.psd.Brush。 |
| x | float | 已绘制文本左上角的 x 坐标。 |
| y | float | 已绘制文本左上角的 y 坐标。 |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


完成在调用 BeginUpdate 后开始的图形操作缓存。调用此方法时，前面的图形操作将一次性应用。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


填充由 com.aspose.psd.PointF 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 FillMode.Alternate 填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的 com.aspose.psd.PointF 结构数组。 |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


使用指定的填充模式填充由 com.aspose.psd.PointF 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的 com.aspose.psd.PointF 结构数组。 |
| 填充模式 | int | com.aspose.psd.FillMode 枚举的成员，用于确定曲线的填充方式。 |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


使用指定的填充模式和张力填充由一组  com.aspose.psd.PointF  结构定义的闭合基数样条曲线的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 定义样条的 com.aspose.psd.PointF 结构数组。 |
| 填充模式 | int | com.aspose.psd.FillMode 枚举的成员，用于确定曲线的填充方式。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


填充由 com.aspose.psd.Point 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 并采用 FillMode.Alternate 填充模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的 com.aspose.psd.Point 结构数组。 |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


使用指定的填充模式填充由 com.aspose.psd.Point 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的 com.aspose.psd.Point 结构数组。 |
| 填充模式 | int | com.aspose.psd.FillMode 枚举的成员，用于确定曲线的填充方式。 |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


使用指定的填充模式和张力填充由一组  com.aspose.psd.Point  结构定义的闭合基数样条曲线的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 定义样条的 com.aspose.psd.Point 结构数组。 |
| 填充模式 | int | com.aspose.psd.FillMode 枚举的成员，用于确定曲线的填充方式。 |
| 张力 | float | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


填充由  com.aspose.psd.Rectangle  结构指定的边界矩形定义的椭圆的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示定义椭圆的边界矩形的 com.aspose.psd.Rectangle 结构。 |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


填充由  com.aspose.psd.RectangleF  结构指定的边界矩形定义的椭圆的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示定义椭圆的边界矩形的 com.aspose.psd.RectangleF 结构。 |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | float | 定义椭圆的边界矩形的宽度。 |
| 高度 | float | 定义椭圆的边界矩形的高度。 |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | int | 定义椭圆的边界矩形的宽度。 |
| 高度 | int | 定义椭圆的边界矩形的高度。 |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


填充  com.aspose.psd.graphicsPath  的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 表示要填充路径的 com.aspose.psd.GraphicsPath。 |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


填充由  com.aspose.psd.RectangleF  结构和两条径向线指定的椭圆定义的饼形区域的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示定义饼块来源椭圆的边界矩形的 com.aspose.psd.Rectangle 结构。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼块第二边的角度（度）。 |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


填充由  com.aspose.psd.RectangleF  结构和两条径向线指定的椭圆定义的饼形区域的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示定义饼块来源椭圆的边界矩形的 com.aspose.psd.RectangleF 结构。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼块第二边的角度（度）。 |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼形区域的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| x | float | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | float | 定义饼块来源椭圆的边界矩形的宽度。 |
| 高度 | float | 定义饼块来源椭圆的边界矩形的高度。 |
| 起始角度 | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| 扫掠角度 | float | 从 startAngle 参数顺时针测量到饼块第二边的角度（度）。 |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼形区域的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| x | int | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | int | 定义饼块来源椭圆的边界矩形的宽度。 |
| 高度 | int | 定义饼块来源椭圆的边界矩形的高度。 |
| 起始角度 | int | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| 扫掠角度 | int | 从 startAngle 参数顺时针测量到饼块第二边的角度（度）。 |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


填充由一组  com.aspose.psd.PointF  结构指定的点以及  FillMode.Alternate  定义的多边形的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 表示要填充多边形顶点的 com.aspose.psd.PointF 结构数组。 |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


使用指定的填充模式填充由一组  com.aspose.psd.PointF  结构指定的点定义的多边形的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 表示要填充多边形顶点的 com.aspose.psd.PointF 结构数组。 |
| fillMode | int | com.aspose.psd.FillMode 枚举的成员，用于确定填充的样式。 |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


使用由 com.aspose.psd.Point 结构指定的点数组以及 FillMode.Alternate，填充多边形的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 表示要填充多边形顶点的 com.aspose.psd.Point 结构数组。 |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


使用指定的填充模式，填充由 com.aspose.psd.Point 结构指定的点数组定义的多边形内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 表示要填充多边形顶点的 com.aspose.psd.Point 结构数组。 |
| fillMode | int | com.aspose.psd.FillMode 枚举的成员，用于确定填充的样式。 |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


填充由 Rectangle 结构指定的矩形内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示要填充矩形的 Rectangle 结构。 |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


填充由 RectangleF 结构指定的矩形内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示要填充矩形的 RectangleF 结构。 |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


填充由一对坐标、宽度和高度指定的矩形内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| x | float | 要填充矩形左上角的 x 坐标。 |
| y | float | 要填充矩形左上角的 y 坐标。 |
| 宽度 | float | 要填充的矩形的宽度。 |
| 高度 | float | 要填充的矩形的高度。 |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


填充由一对坐标、宽度和高度指定的矩形内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| x | int | 要填充矩形左上角的 x 坐标。 |
| y | int | 要填充矩形左上角的 y 坐标。 |
| 宽度 | int | 要填充的矩形的宽度。 |
| 高度 | int | 要填充的矩形的高度。 |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


填充由 RectangleF 结构指定的一系列矩形的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | 表示要填充的矩形的 Rectangle 结构数组。 |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


填充由 Rectangle 结构指定的一系列矩形的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 用于确定填充特性的 Brush。 |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 表示要填充的矩形的 Rectangle 结构数组。 |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


填充 com.aspose.psd.region 的内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 确定填充特性的 com.aspose.psd.Brush。 |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region 表示要填充的区域。 |

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


获取或设置剪裁区域。

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


获取或设置合成质量。

**Returns:**
int - 合成质量。
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


获取此 com.aspose.psd.graphics 的水平分辨率。

**Returns:**
float - 以每英寸点数为单位的值，表示此 com.aspose.psd.graphics 支持的水平分辨率。
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


获取此 com.aspose.psd.graphics 的垂直分辨率。

**Returns:**
float - 以每英寸点数为单位的值，表示此 com.aspose.psd.graphics 支持的垂直分辨率。
### getImage() {#getImage--}
```
public Image getImage()
```


获取图像。

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


获取或设置插值模式。

**Returns:**
int - 插值模式。
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


获取或设置此 com.aspose.psd.graphics 的世界单位与页面单位之间的缩放比例。

**Returns:**
float - 此 com.aspose.psd.graphics 中世界单位与页面单位之间的缩放比例。
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


获取或设置此 com.aspose.psd.graphics 中页面坐标使用的计量单位。

**Returns:**
int - 此 com.aspose.psd.graphics 中页面坐标使用的计量单位。
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


获取或设置图像选项，用于创建可绘制的 vactor 图像。

值：用于创建可绘制矢量图像的图像选项。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


获取或设置平滑模式。

**Returns:**
int - 平滑模式。
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


获取或设置文本呈现提示。

**Returns:**
int - 文本渲染提示。
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取或设置此 com.aspose.psd.graphics 的几何世界变换的副本。

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


获取一个值，指示 graphics 是否处于 BeginUpdate 调用状态。

**Returns:**
boolean - 如果 graphics 处于 BeginUpdate 调用状态则为 True；否则为 false。
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


使用 [GraphicsPath](../../com.aspose.psd/graphicspath) 类测量字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | 字体。 |
| 文本 | java.lang.String | 文本。 |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


测量字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | 字体。 |
|  | 文本 | java.lang.String | 文本。 |

--------------------

GDI 结果几乎总是对斜体无效，且通常对粗体样式无效。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


使用指定的参数测量指定的文本字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 要测量的文本。 |
| font | [Font](../../com.aspose.psd/font) | 要测量的字体。 |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | 布局区域。 |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | 字符串格式。 |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | 获取私有字体缓存。 |
| useMagicNumbersForStyles | boolean | 如果设置为 true [使用样式的魔术数字]。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将表示此 com.aspose.psd.Graphics 的局部几何变换的 com.aspose.psd.Matrix 与指定的 com.aspose.psd.Matrix 相乘，方法是预先添加指定的 com.aspose.psd.matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以几何变换的  com.aspose.psd.Matrix  。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


将表示此 com.aspose.psd.Graphics 的局部几何变换的 com.aspose.psd.Matrix 按指定顺序乘以指定的 com.aspose.psd.Matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以几何变换的  com.aspose.psd.Matrix  。 |
| 顺序 | int | 指定两个矩阵相乘顺序的  com.aspose.psd.MatrixOrder 。 |

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


将 com.aspose.psd.graphics.Transform 属性重置为单位矩阵。

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定量旋转局部几何变换。此方法将在变换前预先添加旋转。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的顺序，以指定的角度旋转本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| 顺序 | int | 一个  com.aspose.psd.MatrixOrder  指定是追加还是预置旋转矩阵。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定量缩放局部几何变换。此方法将在变换前预先添加缩放矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的顺序，以指定的比例缩放本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| 顺序 | int | 一个  com.aspose.psd.MatrixOrder  指定是追加还是预置缩放矩阵。 |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


获取或设置剪裁区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | 剪辑区域。 |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


获取或设置合成质量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 合成质量。 |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


获取或设置插值模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 插值模式。 |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


获取或设置此 com.aspose.psd.graphics 的世界单位与页面单位之间的缩放比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 此 com.aspose.psd.graphics 的世界单位与页面单位之间的缩放比例。 |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


获取或设置此 com.aspose.psd.graphics 中页面坐标使用的计量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此 com.aspose.psd.graphics 中页面坐标使用的计量单位。 |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


获取或设置图像选项，用于创建可绘制的 vactor 图像。

值：用于创建可绘制矢量图像的图像选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


获取或设置平滑模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 平滑模式。 |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


获取或设置文本呈现提示。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 文本呈现提示。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


获取或设置此 com.aspose.psd.graphics 的几何世界变换的副本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | 一个  com.aspose.psd.Matrix  的副本，表示此  com.aspose.psd.graphics 的几何世界变换。 |

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


按指定的尺寸平移本地几何变换。此方法将平移预置到变换之前。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定的顺序，以指定的尺寸平移本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |
| 顺序 | int | 应用平移的顺序（预置或追加）。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

