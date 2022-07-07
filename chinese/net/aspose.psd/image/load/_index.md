---
title: Load
second_title: Aspose.PSD for .NET API 参考
description: 从指定文件加载新图像
type: docs
weight: 20
url: /zh/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

从指定文件加载新图像。

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 加载图像的文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

加载的图像。

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

从指定文件加载新图像。

```csharp
public static Image Load(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 加载图像的文件路径。 |

### 返回值

加载的图像。

### 例子

此示例演示使用指定的文件路径将现有图像文件加载到 Aspose.PSD.Image 的实例中

```csharp
[C#]

//创建图像实例并使用磁盘位置的现有图像文件对其进行初始化
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    //做一些图像处理
}
```

下面的示例演示了通过 ITextPortion 的从右到左语言的文本对齐工作正常。

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

以下示例演示了读取灰度 16 位 PSD 文件并将其保存为每通道 16 位 RGB 的工作正常且无异常。

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // 这里应该也不例外。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

以下示例演示了读取灰度 16 位 PSD 文件并将其保存为每通道 8 位灰度的工作正常且无异常。

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // 这里应该也不例外。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

下面的示例演示文档转换进度正常工作且没有异常。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

以下示例演示了读取和保存灰度 16 位 PSD 文件的工作正常且无异常。

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // 这里应该也不例外。
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

从指定流加载新图像。

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载图像的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

加载的图像。

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

从指定流加载新图像。

```csharp
public static Image Load(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载图像的流。 |

### 返回值

加载的图像。

### 例子

此示例演示使用 System.IO.Stream 对象加载现有图像文件

```csharp
[C#]

//创建一个FileStream实例
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //创建Image类的实例，通过调用Load方法通过FileStream对象加载已有文件
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //做一些图像处理。
    }
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
