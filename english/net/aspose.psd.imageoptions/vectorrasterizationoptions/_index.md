---
title: Class VectorRasterizationOptions
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageOptions.VectorRasterizationOptions class. The vector rasterization options
type: docs
weight: 5410
url: /net/aspose.psd.imageoptions/vectorrasterizationoptions/
---
{{< psd/tize >}}
## VectorRasterizationOptions class

The vector rasterization options.

```csharp
public abstract class VectorRasterizationOptions : ImageOptionsBase
```

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Gets or sets a background color. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Gets or sets the border X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Gets or sets the border Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Gets or sets a value indicating whether center drawing. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). To take proper name of default font can be used next code snippet: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Gets or sets a foreground color. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Gets or sets the page height. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Gets or sets the page size. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Gets or sets the page width. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Gets or sets the smoothing mode. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Gets or sets the text rendering hint. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clones this instance. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Copies to. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |

### See Also

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


