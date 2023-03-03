---
title: Class Graphics
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Graphics 班级. 表示根据当前程序集使用的图形引擎的图形
type: docs
weight: 4310
url: /zh/net/aspose.psd/graphics/
---
## Graphics class

表示根据当前程序集使用的图形引擎的图形。

```csharp
public sealed class Graphics
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Graphics](graphics/)(Image) | 初始化一个新的实例`Graphics`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | 获取或设置剪辑区域。 |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 获取或设置合成质量。 |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | 获取此 Aspose.PSD.Graphics. 的水平分辨率 |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | 获取此 Aspose.PSD.Graphics. 的垂直分辨率 |
| [Image](../../aspose.psd/graphics/image/) { get; } | 获取图像。 |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 获取或设置插值模式。 |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | 获取一个值，指示图形是否处于 BeginUpdate 调用状态。 |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | 获取或设置此 Aspose.PSD.Graphics. 的世界单位和页面单位之间的比例 |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | 获取或设置此 Aspose.PSD.Graphics. 中用于页面坐标的度量单位 |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | 获取或设置平滑模式。 |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示。 |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | 为此获取或设置几何世界变换的副本`Graphics` . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 开始缓存以下图形操作。之后应用的图形效果不会立即应用，而是 EndUpdate 会立即应用所有效果。 |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 使用指定颜色清除图形表面。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | 绘制代表由 a 指定的椭圆的一部分的弧[`Rectangle`](../rectangle/)结构. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | 绘制代表由 a 指定的椭圆的一部分的弧[`RectangleF`](../rectanglef/)结构. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 绘制表示由一对坐标、宽度和高度指定的椭圆的一部分的弧。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 绘制表示由一对坐标、宽度和高度指定的椭圆的一部分的弧。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 绘制由四个定义的贝塞尔样条[`Point`](../point/)结构. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 绘制由四个定义的贝塞尔样条[`PointF`](../pointf/)结构. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 绘制由表示点的四对有序坐标定义的贝塞尔样条。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | 从数组中绘制一系列贝塞尔样条[`PointF`](../pointf/)结构. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | 从数组中绘制一系列贝塞尔样条[`Point`](../point/)结构. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | 绘制由数组定义的闭合基数样条[`PointF`](../pointf/)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | 绘制由数组定义的闭合基数样条[`Point`](../point/)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | 绘制由数组定义的闭合基数样条[`PointF`](../pointf/)使用特定张力的结构。该方法使用默认Alternate填充模式. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 绘制由数组定义的闭合基数样条[`Point`](../point/)使用特定张力的结构。该方法使用默认Alternate填充模式. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 通过指定数组绘制基数样条[`PointF`](../pointf/)结构。此方法使用默认张力 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 通过指定数组绘制基数样条[`Point`](../point/)结构. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 通过指定数组绘制基数样条[`PointF`](../pointf/)使用指定张力的结构. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 通过指定数组绘制基数样条[`Point`](../point/)使用指定张力的结构. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 通过指定数组绘制基数样条[`PointF`](../pointf/)结构。绘图从数组的开头开始偏移。 此方法使用默认张力 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 通过指定数组绘制基数样条[`PointF`](../pointf/)使用特定张力的结构。绘图从数组的开头开始偏移。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 通过指定数组绘制基数样条[`Point`](../point/)使用指定张力的结构. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 绘制由边界指定的椭圆[`Rectangle`](../rectangle/)结构. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 绘制由边界定义的椭圆[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 绘制由一对坐标、高度和宽度指定的边界矩形定义的椭圆。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 绘制由一对坐标、高度和宽度指定的边界矩形定义的椭圆。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 绘制指定[`Image`](./image/)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 绘制指定[`Image`](./image/)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 绘制指定[`Image`](./image/)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 在坐标对指定的位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定的指定部分*image*在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定[`Image`](./image/)在指定位置和指定大小. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 在坐标对指定的位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 绘制不缩放的指定图像，并在必要时对其进行裁剪以适合指定的矩形。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 画一条线连接两个[`Point`](../point/)结构. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 画一条线连接两个[`PointF`](../pointf/)结构. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 绘制连接坐标对指定的两个点的线。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 绘制连接坐标对指定的两个点的线。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | 绘制一系列连接数组的线段[`PointF`](../pointf/)结构. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | 绘制一系列连接数组的线段[`Point`](../point/)结构. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | 绘制一个[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | 绘制由 a 指定的椭圆定义的饼形[`Rectangle`](../rectangle/)结构和两条径向线. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | 绘制由 a 指定的椭圆定义的饼形[`RectangleF`](../rectanglef/)结构和两条径向线. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | 绘制由数组定义的多边形[`PointF`](../pointf/)结构. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | 绘制由数组定义的多边形[`Point`](../point/)结构. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | 绘制由a指定的矩形[`Rectangle`](../rectangle/)结构. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | 绘制由a指定的矩形[`RectangleF`](../rectanglef/)结构. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | 绘制一系列指定的矩形[`RectangleF`](../rectanglef/)结构. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | 绘制一系列指定的矩形[`Rectangle`](../rectangle/)结构. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 在指定位置用指定的字符绘制指定的文本字符串[`Brush`](../brush/)和[`Font`](../font/)对象. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 在指定矩形内绘制指定文本字符串[`Brush`](../brush/)和[`Font`](../font/)对象. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 在指定位置用指定的字符绘制指定的文本字符串[`Brush`](../brush/)和[`Font`](../font/)对象. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 在指定位置用指定的字符绘制指定的文本字符串[`Brush`](../brush/)和[`Font`](../font/)使用指定格式属性的对象[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 在指定矩形内绘制指定文本字符串[`Brush`](../brush/)和[`Font`](../font/)使用指定格式属性的对象[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 在指定位置用指定的字符绘制指定的文本字符串[`Brush`](../brush/)和[`Font`](../font/)使用指定格式属性的对象[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | 完成调用 BeginUpdate 后启动的图形操作的缓存。调用此方法时会立即应用前面的图形操作。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf/)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point/)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf/)使用指定填充模式的结构。此方法使用默认张力 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point/)使用指定填充模式的结构。此方法使用默认张力 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf/)使用指定填充模式和张力的结构。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point/)使用指定填充模式和张力的结构。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | 填充由 a 指定的边界矩形定义的椭圆的内部[`Rectangle`](../rectangle/)结构. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | 填充由 a 指定的边界矩形定义的椭圆的内部[`RectangleF`](../rectanglef/)结构. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | 填充 a 的内部[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | 填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../rectanglef/)结构和两条径向线. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | 填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../rectanglef/)结构和两条径向线. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 填充由指定的点数组定义的多边形的内部[`PointF`](../pointf/)结构和Alternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 填充由指定的点数组定义的多边形的内部[`Point`](../point/)结构和Alternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 填充由指定的点数组定义的多边形的内部[`PointF`](../pointf/)使用指定填充模式的结构. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 填充由指定的点数组定义的多边形的内部[`Point`](../point/)使用指定填充模式的结构. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | 填充由 a 指定的矩形的内部[`Rectangle`](../rectangle/)结构. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | 填充由 a 指定的矩形的内部[`RectangleF`](../rectanglef/)结构. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | 填充由指定的一系列矩形的内部[`RectangleF`](../rectanglef/)结构. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | 填充由指定的一系列矩形的内部[`Rectangle`](../rectangle/)结构. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | 填充 a 的内部[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | 乘以[`Matrix`](../matrix/)表示这个的局部几何变换`Graphics`由指定的[`Matrix`](../matrix/)通过预先指定[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 乘以[`Matrix`](../matrix/)表示这个的局部几何变换`Graphics`由指定的[`Matrix`](../matrix/)按指定顺序. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | 重置[`Transform`](./transform/)属性到身份. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | 按指定量旋转局部几何变换。此方法将旋转添加到 transform. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定顺序按指定量旋转局部几何变换。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到 transform. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序按指定数量缩放局部几何变换。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将翻译添加到 transform. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序按指定尺寸平移局部几何变换。 |

### 例子

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建了一个 PSD 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面绘制原始形状，然后将其导出为 PSD 文件格式。

```csharp
[C#]

//创建图像实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //通过指定具有黑色的 Pen 对象绘制弧形， 
    //围绕圆弧、起始角和扫描角的矩形
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //通过指定具有蓝色和坐标点的 Pen 对象来绘制贝塞尔曲线。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //通过指定具有绿色和点数组的 Pen 对象来绘制曲线
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //使用 Pen 对象和周围的矩形绘制一个椭圆
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //画一条线 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //绘制饼图
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //通过指定具有红色和点数组的 Pen 对象来绘制多边形
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //画一个矩形
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //创建一个SolidBrush对象并设置它的各种属性
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //在特定点使用 SolidBrush 对象和字体绘制字符串
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //创建一个PngOptions实例并设置它的各种属性
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 保存所有更改。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


