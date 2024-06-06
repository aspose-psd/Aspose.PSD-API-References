---
title: Class FileCreateSource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Sources.FileCreateSource class. Represents a file source for creation
type: docs
weight: 5880
url: /net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Represents a file source for creation.

```csharp
public sealed class FileCreateSource : FileSource
```

## Constructors

| Name | Description |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initializes a new instance of the `FileCreateSource` class. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initializes a new instance of the `FileCreateSource` class. |

## Properties

| Name | Description |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Gets the file path to create. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Gets a value indicating whether file will be temporal. |

## Methods

| Name | Description |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Gets the stream container. |

## Examples

This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface. The example creates a new Image and draw shapes using Figures and GraphicsPath

```csharp
[C#]

//Creates an instance of Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Creates and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clears Graphics surface
    graphics.Clear(Color.Wheat);

    //Creates an instance of Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Create an instance of SolidBrush having Red Color
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Draw a String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // create export options.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // save all changes
    image.Save("C:\\temp\\output.gif", options);
}
```

### See Also

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


