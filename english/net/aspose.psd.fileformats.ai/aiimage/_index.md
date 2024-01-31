---
title: Class AiImage
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Ai.AiImage class. The Adobe Illustrator AI Image
type: docs
weight: 1270
url: /net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

The Adobe Illustrator (AI) Image.

```csharp
public sealed class AiImage : Image
```

## Constructors

| Name | Description |
| --- | --- |
| [AiImage](aiimage/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Gets or sets the index of the active page. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Gets the [`Image`](../../aspose.psd/image/) container. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Gets the data section. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Gets a value of file format. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Gets the finalize section. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Gets the header. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Gets the image height. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Gets the layer sections. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Gets the setup section. |
| [Size](../../aspose.psd/image/size/) { get; } | Gets the image size. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Gets the version of Adobe Illustrator format. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Adds the AI layer section. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Gets the default options. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.psd/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.psd/image/save/) method as the second parameter. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.psd/image/save/)() | Saves the image data to the underlying stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Saves the object's data to the specified file location. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |

## Examples

The following example demonstrates how you can export Adobe Illustrator files to PDF format in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

The following example demonstrates how you can export AI file to PSD and PNG format in Aspose.PSD

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

The following example demonstrates the support of the exporting Ai format to PSD, PNG, JPG, GIF and TIF formats.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### See Also

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


