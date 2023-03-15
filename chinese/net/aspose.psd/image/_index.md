---
title: Class Image
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Image 班级. 图像是所有类型图像的基类
type: docs
weight: 4590
url: /zh/net/aspose.psd/image/
---
## Image class

图像是所有类型图像的基类。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取`Image`容器. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式 的值 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置图像是否有背景色的值。 |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 获取图像高度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取对象数据当前是否缓存，不需要读取数据的值。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像大小。 |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 获取图像宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 使用指定的创建选项创建新图像。 |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 从指定流加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 从指定文件加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 从指定流加载新图像。 |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 从指定文件加载新图像。 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存[`Save`](../datastreamsupporter/save/)方法，将生成每像素 8 位的输出 PNG 图像。 要避免它并保存每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](./save/)方法作为第二个参数. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 调整图像大小。默认值LeftTopToLeftTop使用. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/#save)() | 将图像数据保存到底层流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 确定是否可以从指定流中加载图像。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 判断是否可以从指定文件路径加载图片。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 确定图像是否可以从指定的流中加载并可选地使用指定的*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 确定是否可以从指定的文件路径加载图像并可选择使用指定的打开选项。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | 获取文件格式。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | 获取文件格式。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 获取适合当前图像的矩形。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 获取适合当前图像的矩形。 |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 获取比例高度。 |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | 获取比例宽度。 |

### 例子

此示例在 PsdOptions 实例的 Source 属性指定的某个磁盘位置创建一个新的图像文件。在创建实际图像之前设置 PsdOptions 实例的几个属性。特别是 Source 属性，在这种情况下指的是实际磁盘位置。

```csharp
[C#]

//创建 PsdOptions 实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其指定为 PsdOptions 实例的源
//第二个布尔参数确定要创建的文件是否为IsTemporal
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建Image的实例并通过调用Create方法用PsdOptions的实例初始化它
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 也可以看看

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


