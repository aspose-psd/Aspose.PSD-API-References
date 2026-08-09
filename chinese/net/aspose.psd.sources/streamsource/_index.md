---
title: "类 StreamSource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Sources.StreamSource 类。表示流源。"
type: docs
weight: 6120
url: /zh/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

表示流源。

```csharp
public sealed class StreamSource : Source
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | 初始化 `StreamSource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | 获取一个值，指示在容器被释放时是否应释放流。 |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | 获取流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | 获取流容器。 |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


