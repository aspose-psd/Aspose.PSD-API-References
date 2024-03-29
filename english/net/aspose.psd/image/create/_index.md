---
title: Image.Create
second_title: Aspose.PSD for .NET API Reference
description: Image method. Creates a new image using the specified create options
type: docs
weight: 10
url: /net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Creates a new image using the specified create options.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | The image options. |
| width | Int32 | The width. |
| height | Int32 | The height. |

### Return Value

The newly created image.

## Examples

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

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


