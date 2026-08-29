---
title: "类 GraphicsPath"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.GraphicsPath 类。表示一系列相连的直线和曲线。此类不可被继承"
type: docs
weight: 4790
url: /zh/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

表示一系列相连的直线和曲线。此类不可继承。

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | 初始化 `GraphicsPath` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | 获取或设置对象的边界。 |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | 获取路径图形。 |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | 获取或设置一个 [`FillMode`](../fillmode/) 枚举，用于确定此 `GraphicsPath` 中形状内部的填充方式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 添加一个新图形。 |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 添加新图形。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 将指定的 `GraphicsPath` 附加到此路径。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 将指定的 `GraphicsPath` 附加到此路径。 |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | 对该图形路径执行深度克隆。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 应用指定的变换，然后将此 `GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | 将此 `GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 绘制并使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 绘制并使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 绘制并使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 绘制并使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 的轮廓内部（下方）。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 指示指定的点是否位于指定的 [`Graphics`](../graphics/) 可见裁剪区域内的此 `GraphicsPath` 中。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 指示使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 内部。 |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 移除一个图形。 |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 移除多个图形。 |
| [Reset](../../aspose.psd/graphicspath/reset/)() | 清空图形路径并将 [`FillMode`](../fillmode/) 设置为 Alternate。 |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | 反转此 `GraphicsPath` 中每个形状的图形、形状和点的顺序。 |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 将指定的变换应用于形状。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | 为路径添加额外的轮廓。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | 为 `GraphicsPath` 添加额外的轮廓。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | 用在使用指定笔绘制此路径时填充的区域所包围的曲线替换此 `GraphicsPath`。 |

## 示例

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新 Image 并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类公开的 DrawPath 方法在表面上渲染路径。最终图像导出为 Tiff 文件格式。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //创建 GraphicsPath 类的实例
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //创建 Figure 类的实例
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //向 Figure 对象添加形状
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //将 Figure 对象添加到 GraphicsPath
    graphicspath.AddFigure(figure);

    //使用颜色为 Black 的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //创建 TiffOptions 的实例并设置其各种属性
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 保存所有更改。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 另请参阅

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


