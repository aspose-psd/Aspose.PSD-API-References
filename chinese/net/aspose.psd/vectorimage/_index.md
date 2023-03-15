---
title: Class VectorImage
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.VectorImage 班级. 矢量图像是所有类型矢量图像的基类
type: docs
weight: 5720
url: /zh/net/aspose.psd/vectorimage/
---
## VectorImage class

矢量图像是所有类型矢量图像的基类。

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取[`Image`](../image/)容器. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式 的值 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置图像是否有背景色的值。 |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | 获取对象高度，以英寸为单位。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取对象数据当前是否缓存，不需要读取数据的值。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像大小。 |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | 获取对象大小，以英寸为单位。 |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | 获取对象宽度，以英寸为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存[`Save`](../datastreamsupporter/save/)方法，将生成每像素 8 位的输出 PNG 图像。 要避免它并保存每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../image/save/)方法作为第二个参数. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。默认值LeftTopToLeftTop使用. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |

### 也可以看看

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


