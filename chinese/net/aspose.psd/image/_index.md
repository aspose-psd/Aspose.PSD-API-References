---
title: "Image 类"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Image 类。Image 是所有图像类型的基类。"
type: docs
weight: 5060
url: /zh/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

图像是所有类型图像的基类。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 获取图像每像素位数的计数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取 `Image` 容器。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置一个值，指示图像是否具有背景颜色。 |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 获取图像高度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 获取指示是否使用图像调色板的值。 |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 使用指定的创建选项创建新图像。 |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 从指定的流加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 从指定的文件加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 从指定的流加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 从指定的文件加载新图像。 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) 加载额外数据。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以使用传入的保存选项保存为指定的文件格式。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../datastreamsupporter/save/) 方法保存，它将生成每像素 8 位的 PNG 输出图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](./save/) 方法。 |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 调整图像大小。使用默认的 NearestNeighbourResample。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/#save)() | 将图像数据保存到底层流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 确定是否可以从指定的流加载图像。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 确定是否可以从指定的文件路径加载图像。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 确定是否可以从指定的流加载图像，且可选地使用指定的 *loadOptions*。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | 获取文件格式。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | 获取文件格式。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 获取适合当前图像的矩形。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 获取适合当前图像的矩形。 |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 获取等比例高度。 |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | 获取比例宽度。 |

## 示例

此示例在由 PsdOptions 实例的 Source 属性指定的磁盘位置创建一个新的 Image 文件。在创建实际图像之前，会设置 PsdOptions 实例的多个属性。尤其是指向此案例实际磁盘位置的 Source 属性。

```csharp
[C#]

//创建 PsdOptions 的实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其分配为 PsdOptions 实例的 Source
//第二个布尔参数决定要创建的文件是否为临时文件
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建 Image 的实例，并通过调用 Create 方法使用 PsdOptions 实例进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //进行一些图像处理。

    // 保存所有更改
    image.Save();
}
```

### 另请参阅

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


