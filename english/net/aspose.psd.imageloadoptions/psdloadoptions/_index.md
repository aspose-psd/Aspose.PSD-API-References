---
title: Class PsdLoadOptions
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions class. Psd load options
type: docs
weight: 5080
url: /net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Psd load options

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Gets or sets whether to save with the rendered image, with or without a warp transform. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Gets or sets the [`Image`](../../aspose.psd/image/) background [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Gets or sets the data recovery mode. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Gets or sets a value indicating whether [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). When set this option only supported effects will be rendered to final merged image. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Gets or sets a value indicating whether [use read only mode]. This is read-only mode, supported for identical compatibility with Adobe Photoshop. When this option is set, all changes applied for layers will not be saved to final image. All data is used from ImageData section, so it is identical to Photoshop. By default all loaded images are not identical to Adobe Photoshop compatible. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Gets or sets a value indicating whether ICC profile conversion should be applied. |

## Examples

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

### See Also

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


