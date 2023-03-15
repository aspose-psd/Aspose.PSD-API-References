---
title: Class GraphicsPath
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.GraphicsPath 班级. 代表一系列相连的直线和曲线此类不能被继承
type: docs
weight: 4320
url: /zh/net/aspose.psd/graphicspath/
---
## GraphicsPath class

代表一系列相连的直线和曲线。此类不能被继承。

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | 初始化一个新的实例`GraphicsPath`类. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | 初始化一个新的实例`GraphicsPath`类. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | 初始化一个新的实例`GraphicsPath`类. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | 初始化一个新的实例`GraphicsPath`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | 获取或设置对象的边界。 |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | 获取路径数字。 |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | 获取或设置一个[`FillMode`](../fillmode/)确定形状内部如何在这个中的枚举`GraphicsPath`已满. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 添加一个新图形。 |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 添加新图形。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 追加指定的`GraphicsPath`到这条路. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 追加指定的`GraphicsPath`到这条路. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | 执行此图形路径的深度克隆。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | 将此路径中的每条曲线转换为一系列连接的线段。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 应用指定的变换，然后在此转换每条曲线`GraphicsPath`成一系列连接的线段. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | 转换每条曲线`GraphicsPath`成一系列连接的线段. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/)并使用指定的[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/)并使用指定的[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/)并使用指定的[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 表示指定点是否包含在这个轮廓之内（下）`GraphicsPath`当用指定的绘制[`Pen`](../pen/)并使用指定的[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 表示指定点是否包含在此`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 表示指定点是否包含在此`GraphicsPath`在指定的可见剪辑区域[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 表示指定点是否包含在此`GraphicsPath` , 使用指定的[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 删除图形。 |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 删除图形。 |
| [Reset](../../aspose.psd/graphicspath/reset/)() | 清空图形路径并设置[`FillMode`](../fillmode/)到Alternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | 颠倒图形、形状和每个形状中的点的顺序`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 将指定的变换应用于形状。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 将由矩形和平行四边形定义的扭曲变换应用于此`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 将由矩形和平行四边形定义的扭曲变换应用于此`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 将由矩形和平行四边形定义的扭曲变换应用于此`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 将由矩形和平行四边形定义的扭曲变换应用于此`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | 向路径添加附加轮廓。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | 添加额外的大纲`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | 替换这个`GraphicsPath`当此路径由指定的笔绘制时，曲线包围填充的区域。 |

### 例子

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新图像并在 GraphicsPath 类的帮助下绘制路径。最后调用 Graphics 类公开的 DrawPath 方法以在表面上呈现路径。最后将图像导出为 Tiff 文件格式。

```csharp
[C#]

//创建图像实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建GraphicsPath类的一个实例
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //创建图类实例
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //将Shapes添加到Figure对象
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //将Figure对象添加到GraphicsPath
    graphicspath.AddFigure(figure);

    //使用颜色为黑色的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //创建一个 TiffOptions 实例并设置它的各种属性
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 保存所有更改。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 也可以看看

* class [ObjectWithBounds](../objectwithbounds/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


