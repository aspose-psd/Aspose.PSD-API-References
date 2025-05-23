---
title: Class PsdOptions
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageOptions.PsdOptions class. The psd file format create options
type: docs
weight: 5290
url: /net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

The psd file format create options.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Initializes a new instance of the `PsdOptions` class. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Initializes a new instance of the `PsdOptions` class. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Initializes a new instance of the `PsdOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Gets or sets the color of background. It can be seen under transparent objects. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Gets or sets the bits count per color channel. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Gets or sets the color channels count. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Gets or sets the psd color mode. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Gets or sets the psd compression method. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). To take proper name of default font can be used next code snippet: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Gets or sets the file format version. It can be PSD or PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers. Please note, text layers drawing to final layout is not supported for Compact Framework platform |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -&gt; "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Gets or sets the psd resources. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Gets or sets a value indicating whether [update metadata]. If the value is true, the metadata will be updated while saving an image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Gets or sets the psd file version. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Get or set XMP data container |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clones this instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |

## Examples

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

This example creates a new Image file at some disk location as specified by Source property of the PsdOptions instance. Several properties for PsdOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case.

```csharp
[C#]

//Create an instance of PsdOptions and set its various properties
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Create an instance of FileCreateSource and assign it as Source for the instance of PsdOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Create an instance of Image and initialize it with instance of PsdOptions by calling Create method
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //do some image processing

    // save all changes
    image.Save();
}
```

The following example demonstrates that reading and saving the Grayscale 16 bit PSD files to 16bit per channel RGB works correctly and without an exception.

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
    // Here should be no exception.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

The following example demonstrates that reading and saving the Grayscale 16 bit PSD files to 8 bit per channel Grayscale works correctly and without an exception.

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
    // Here should be no exception.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

The following example demonstrates how you can use the PassThrough layer blend mode in Aspose.PSD

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

The following example demonstrates that the document conversion progress works correctly and without an exception.

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

This example shows how to Loads Pixel information in an Array of Type Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in PSD format) using MemoryStream object.

```csharp
[C#]

//Create an instance of MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Create an instance of PsdOptions and set its various properties including the Source property
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Create an instance of Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Get the pixels of image by specifying the area as image boundary
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over the Array and sets color of alrenative indexed pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Set the indexed pixel color to yellow
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Set the indexed pixel color to blue
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Apply the pixel changes to the image
        image.SavePixels(image.Bounds, pixels);

        // save all changes.
        image.Save();
    }

    //Write MemoryStream to File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

The following example demonstrates that reading and saving the Grayscale 16 bit PSD files works correctly and without an exception.

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
        // Here should be no exception.
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

### See Also

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


