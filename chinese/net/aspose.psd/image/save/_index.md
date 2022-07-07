---
title: Save
second_title: Aspose.PSD for .NET API 参考
description: 将图像数据保存到底层流
type: docs
weight: 230
url: /zh/net/aspose.psd/image/save/
---
## Save() {#save}

将图像数据保存到底层流。

```csharp
public void Save()
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |

### 例子

以下示例演示如何将 Adobe Illustrator 文件导出为 Aspose.PSD 中的 PDF 格式

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

以下示例演示 AsposePSD 支持将 PSB 文件导出为 PSD 格式。

```csharp
[C#]

// 支持将 PSB 保存为 PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

以下代码将 PsdImage 保存为带有可选文本的 PDF 文档。

```csharp
[C#]

// 将 PSD 保存为 PDF 不提供可选文本
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

以下示例演示如何将 AI 文件导出为 Aspose.PSD 中的 PSD 和 PNG 格式

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

以下示例演示文本通过 ITextPortion 对齐从右到左的语言可以正常工作。

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

此示例显示保存图像的简单步骤。为了演示此操作，我们从某个磁盘位置加载现有文件，对图像执行旋转操作并使用文件路径将图像保存为 Jpeg 文件格式

```csharp
[C#]

//创建一个image类的实例，并通过File path用已有的文件对其进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //将图像绕X轴旋转180度
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //使用默认 JpegOptions 设置将图像另存为 Jpeg 到文件路径
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

以下示例演示如何可以更改 Aspose.PSD 中的 LayerGroup 可见性

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 更改图层名称并保存
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 关闭组内的所有内容
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

以下示例演示了如果在 Aspose.PSD 中使用简单构造函数版本，您如何在新创建的图层上绘图

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // 用钢笔工具画一个矩形
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 用蓝色实心笔刷绘制另一个矩形
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

以下示例演示如何在 Aspose.PSD 中使用 PassThrough 图层混合模式

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

以下示例演示文档转换进度正常工作，无一例外。

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

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。为使用源边界设置空矩形。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 选项 |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | 图像保存失败。 |

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

根据保存选项，将图像数据以指定的文件格式保存到指定的流中。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 无法保存为指定的格式，因为在时刻。；optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | 图像导出失败。 |

### 例子

这个例子展示了将图像保存到 MemoryStream 的过程。为了演示此操作，示例从某个磁盘位置加载现有文件，对图像执行旋转操作并以 Gif 格式保存图像

```csharp
[C#]

//创建一个MemoryStream实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建一个image类的实例，并通过File path用已有的文件对其进行初始化
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //将图像绕X轴旋转180度
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //使用默认 GifOptions 设置将图像作为 PSD 保存到 MemoryStream
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

根据保存选项，将图像数据以指定的文件格式保存到指定的流中。

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 无法保存为指定的格式，因为在时刻。；optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | 图像导出失败。 |

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* 命名空间 [Aspose.PSD](../../image)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
