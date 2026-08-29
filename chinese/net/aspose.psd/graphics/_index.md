---
title: "类 Graphics"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Graphics 类。表示根据当前程序集使用的图形引擎的图形。"
type: docs
weight: 4780
url: /zh/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

根据当前程序集使用的图形引擎表示图形。

```csharp
public sealed class Graphics
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Graphics](graphics/)(Image) | 初始化 `Graphics` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | 获取或设置剪辑区域。 |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 获取或设置合成质量。 |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | 获取此 Aspose.PSD.Graphics 的水平分辨率。 |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | 获取此 Aspose.PSD.Graphics 的垂直分辨率。 |
| [Image](../../aspose.psd/graphics/image/) { get; } | 获取图像。 |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 获取或设置插值模式。 |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | 获取一个值，指示图形是否处于 BeginUpdate 调用状态。 |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | 获取或设置此 Aspose.PSD.Graphics 的世界单位与页面单位之间的缩放比例。 |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | 获取或设置此 Aspose.PSD.Graphics 中页面坐标使用的度量单位。 |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | 获取或设置图像选项，用于创建可绘制的矢量图像。 |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | 获取或设置平滑模式。 |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示。 |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | 获取或设置此 `Graphics` 的几何世界变换的副本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 开始缓存以下图形操作。随后应用的图形效果不会立即生效，而是等到 EndUpdate 时一次性应用所有效果。 |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 使用指定的颜色清除图形表面。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | 绘制由 [`Rectangle`](../rectangle/) 结构指定的椭圆的一段弧线。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | 绘制由 [`RectangleF`](../rectanglef/) 结构指定的椭圆的一段弧线。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 绘制由四个 [`Point`](../point/) 结构定义的贝塞尔样条。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 绘制由四个 [`PointF`](../pointf/) 结构定义的贝塞尔样条。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 绘制由四对有序坐标（表示点）定义的贝塞尔样条。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | 从 [`PointF`](../pointf/) 结构数组绘制一系列贝塞尔样条。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | 从 [`Point`](../point/) 结构数组绘制一系列贝塞尔样条。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | 绘制由 [`PointF`](../pointf/) 结构数组定义的闭合基数样条。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | 绘制由 [`Point`](../point/) 结构数组定义的闭合基数样条。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | 绘制由 [`PointF`](../pointf/) 结构数组定义的闭合基数样条，使用指定的张力。此方法使用默认的 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 使用指定的张力绘制由一组 [`Point`](../point/) 结构定义的闭合基数样条。此方法使用默认的 Alternate 填充模式。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 通过指定的 [`PointF`](../pointf/) 结构数组绘制基数样条。此方法使用默认张力 0.5。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 通过指定的 [`Point`](../point/) 结构数组绘制基数样条。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 使用指定的张力，通过指定的 [`PointF`](../pointf/) 结构数组绘制基数样条。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 使用指定的张力，通过指定的 [`Point`](../point/) 结构数组绘制基数样条。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 通过指定的 [`PointF`](../pointf/) 结构数组绘制基数样条。绘制从数组起始位置偏移开始。此方法使用默认张力 0.5。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 使用指定的张力，通过指定的 [`PointF`](../pointf/) 结构数组绘制基数样条。绘制从数组起始位置偏移开始。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 使用指定的张力，通过指定的 [`Point`](../point/) 结构数组绘制基数样条。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 绘制由边界 [`Rectangle`](../rectangle/) 结构指定的椭圆。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 绘制由边界 [`RectangleF`](../rectanglef/) 定义的椭圆。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 在指定位置绘制指定的 [`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 在指定位置绘制指定的 [`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 在指定位置绘制指定的 [`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 在由坐标对指定的位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的 [`Image`](./image/)。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 在由坐标对指定的位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 绘制指定的图像且不进行缩放，如有必要会裁剪以适应指定的矩形。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 绘制连接两个 [`Point`](../point/) 结构的直线。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 绘制连接两个 [`PointF`](../pointf/) 结构的直线。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 绘制连接由坐标对指定的两点的直线。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 绘制连接由坐标对指定的两点的直线。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | 绘制一系列连接 [`PointF`](../pointf/) 结构数组的线段。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | 绘制一系列连接 [`Point`](../point/) 结构数组的线段。 |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | 绘制一个 [`GraphicsPath`](../graphicspath/)。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | 绘制由 [`Rectangle`](../rectangle/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | 绘制由 [`RectangleF`](../rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | 绘制由一组 [`PointF`](../pointf/) 结构定义的多边形。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | 绘制由一组 [`Point`](../point/) 结构定义的多边形。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | 绘制由 [`Rectangle`](../rectangle/) 结构指定的矩形。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | 绘制由 [`RectangleF`](../rectanglef/) 结构指定的矩形。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | 绘制由 [`RectangleF`](../rectanglef/) 结构指定的一系列矩形。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | 绘制由 [`Rectangle`](../rectangle/) 结构指定的一系列矩形。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 在指定位置使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 在指定的矩形中使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 在指定位置使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 在指定位置使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象，并使用指定的 [`StringFormat`](../stringformat/) 的格式属性绘制指定的文本字符串。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 在指定的矩形中使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象，并使用指定的 [`StringFormat`](../stringformat/) 的格式属性绘制指定的文本字符串。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 在指定位置使用指定的 [`Brush`](../brush/) 和 [`Font`](../font/) 对象，并使用指定的 [`StringFormat`](../stringformat/) 的格式属性绘制指定的文本字符串。 |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | 完成在调用 BeginUpdate 后开始的图形操作缓存。调用此方法时，之前的图形操作将一次性应用。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | 填充由一组 [`PointF`](../pointf/) 结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和交替填充模式。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | 填充由一组 [`Point`](../point/) 结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和交替填充模式。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | 使用指定的填充模式填充由一组 [`PointF`](../pointf/) 结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | 使用指定的填充模式填充由一组 [`Point`](../point/) 结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | 使用指定的填充模式和张力填充由一组 [`PointF`](../pointf/) 结构定义的闭合基数样条曲线的内部。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | 使用指定的填充模式和张力填充由一组 [`Point`](../point/) 结构定义的闭合基数样条曲线的内部。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | 填充由 [`Rectangle`](../rectangle/) 结构指定的边界矩形定义的椭圆内部。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的边界矩形定义的椭圆内部。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆内部。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆内部。 |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | 填充 [`GraphicsPath`](../graphicspath/) 的内部。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的椭圆以及两条径向线定义的饼形区域的内部。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的椭圆以及两条径向线定义的饼形区域的内部。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 填充由[`PointF`](../pointf/)结构指定的点数组定义的多边形内部，并使用 Alternate。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 填充由[`Point`](../point/)结构指定的点数组定义的多边形内部，并使用 Alternate。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 填充由[`PointF`](../pointf/)结构指定的点数组定义的多边形内部，使用指定的填充模式。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 填充由[`Point`](../point/)结构指定的点数组定义的多边形内部，使用指定的填充模式。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | 填充由[`Rectangle`](../rectangle/)结构指定的矩形内部。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | 填充由[`RectangleF`](../rectanglef/)结构指定的矩形内部。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的矩形内部。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的矩形内部。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | 填充由[`RectangleF`](../rectanglef/)结构指定的一系列矩形的内部。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | 填充由[`Rectangle`](../rectangle/)结构指定的一系列矩形的内部。 |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | 填充[`Region`](../region/)的内部。 |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | 将表示此 `Graphics` 的局部几何变换的[`Matrix`](../matrix/)乘以指定的[`Matrix`](../matrix/)，方法是预先添加指定的[`Matrix`](../matrix/)。 |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 将表示此 `Graphics` 的局部几何变换的[`Matrix`](../matrix/)乘以指定的[`Matrix`](../matrix/)，按照指定的顺序。 |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | 将 [`Transform`](./transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | 按指定的角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定的角度并按照指定的顺序旋转本地几何变换。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | 按指定的比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定的比例并按照指定的顺序缩放本地几何变换。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | 按指定的尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定的尺寸并按照指定的顺序平移本地几何变换。 |

## 示例

此示例使用 Graphics 类在 Image 表面创建原始形状。为了演示该操作，示例创建一个 PSD 格式的新 Image，并使用 Graphics 类公开的 Draw 方法在 Image 表面绘制原始形状，然后将其导出为 PSD 文件格式。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //通过指定具有黑色的 Pen 对象来绘制弧线，
    //一个围绕弧线的 Rectangle、起始角度和扫掠角度
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //通过指定具有蓝色的 Pen 对象和坐标点来绘制贝塞尔曲线。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //通过指定具有绿色的 Pen 对象和点数组来绘制曲线
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //绘制直线
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //绘制饼形段
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //通过指定具有红色的 Pen 对象和点数组来绘制多边形
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //绘制矩形
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //创建 SolidBrush 对象并设置其各种属性
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //使用 SolidBrush 对象和 Font 在特定点绘制字符串
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //创建 PngOptions 实例并设置其各种属性
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 保存所有更改。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


