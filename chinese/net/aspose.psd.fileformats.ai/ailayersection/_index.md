---
title: "类 AiLayerSection"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Ai.AiLayerSection 类。Ai 格式的图层段"
type: docs
weight: 1280
url: /zh/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Ai 格式图层段

```csharp
public sealed class AiLayerSection : AiDataSection
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | 获取或设置蓝色分量。 |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | 获取或设置颜色的索引。此参数的取值范围为 –1 到 26。每个整数代表一种颜色，可分配给图层以供用户识别。 |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | 获取或设置颜色编号。-1 表示来自红、绿、蓝属性的自定义颜色值。指定图层的颜色设置。 |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | 获取或设置暗淡值（百分比）。将图层中链接的图像和位图图像的强度降低到指定的百分比。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | 获取或设置绿色分量。 |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | 获取或设置一个值，指示此实例是否具有多图层蒙版。 |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | 获取或设置一个值，指示此图层是否被暗淡。降低图层中链接的图像和位图图像的强度。 |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | 获取或设置一个值，指示此图层是否被锁定。防止对该项目进行更改。 |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | 获取或设置一个值，指示此图层是否为预览。以彩色而非轮廓显示图层中的艺术作品。 |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | 获取或设置一个值，指示此图层是否可打印。如果为 true，则使图层中的艺术作品可打印。 |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | 获取或设置一个值，指示此图层是否可见。如果为 true，则在画板上显示图层中包含的所有艺术作品。 |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | 获取或设置一个值，指示此图层是否为模板图层。 |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | 获取或设置图层名称。指定项目在图层面板中显示的名称。 |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | 获取栅格图像。 |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | 获取或设置红色分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | 添加栅格图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | 获取字符串数据。 |

## 示例

以下代码演示了如何在 AI 格式文件中加载栅格图像的设置。

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### 另请参阅

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


