---
title: "类 VectorImage"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.VectorImage 类。向量图像是所有类型向量图像的基类"
type: docs
weight: 6220
url: /zh/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

矢量图像是所有类型矢量图像的基类。

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 获取图像每像素位数的计数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取 [`Image`](../image/) 容器。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置一个值，指示图像是否具有背景颜色。 |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | 获取对象的高度（英寸）。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 获取指示是否使用图像调色板的值。 |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | 获取对象的宽度（英寸）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) 加载额外数据。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以使用传入的保存选项保存为指定的文件格式。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。这对于保持原始图像的位深度和其他参数不变很有帮助。例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../datastreamsupporter/save/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将它们作为第二个参数传递给 [`Save`](../image/save/) 方法。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。使用默认的 NearestNeighbourResample。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |

### 另请参阅

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


