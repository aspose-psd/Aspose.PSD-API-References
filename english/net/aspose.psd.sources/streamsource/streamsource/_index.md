---
title: StreamSource.StreamSource
second_title: Aspose.PSD for .NET API Reference
description: StreamSource constructor. Initializes a new instance of the StreamSource class
type: docs
weight: 10
url: /net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Initializes a new instance of the [`StreamSource`](../) class.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to open. |

## Examples

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

### See Also

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initializes a new instance of the [`StreamSource`](../) class.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to open. |
| disposeStream | Boolean | if set to `true` the stream will be disposed. |

## Examples

This example demonstrates the use of System.IO.Stream to Create a new Image file

```csharp
[C#]

//Creates an instance of PsdOptions and set its various properties
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Create an instance of System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Define the source property for the instance of PsdOptions
//Second boolean parameter determins if the Stream is disposed once get out of scope
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Creates an instance of Image and call Create method with PsdOptions as parameter to initialize the Image object   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //do some image processing
}
```

### See Also

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


