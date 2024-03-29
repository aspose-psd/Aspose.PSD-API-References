---
title: Layer.Layer
second_title: Aspose.PSD for .NET API Reference
description: Layer constructor. Initializes a new instance of the Layer class. Constructor for lazy initialization
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

Initializes a new instance of the [`Layer`](../) class. Constructor for lazy initialization.

```csharp
public Layer()
```

## Examples

The following example demonstrates how you can draw on a newly created layer if the simple constructor version is used in Aspose.PSD

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

    // draw a rectangle with Pen tool
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // draw another rectangle with Solid Brush in Blue color
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initializes a new instance of the [`Layer`](../) class.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image. |
| disposeImage | Boolean | if set to `true` [dispose image]. |

## Examples

The following code demonstrates ability to load JPEG/PNG/etc image files to PsdImage without direct loading.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### See Also

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initializes a new instance of the [`Layer`](../) class.

```csharp
public Layer(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The image stream |

## Examples

The following example demonstrates how you can add Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif images as layers to PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initializes a new instance of the [`Layer`](../) class from byte arrays.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | Rectangle | The layer bounds. |
| redBytes | Byte[] | The red bytes. |
| greenBytes | Byte[] | The green bytes. |
| blueBytes | Byte[] | The blue bytes. |
| name | String | The layer name. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Byte arrays can not be empty or Byte arrays length must equal bounds dimensions (bounds.Width * bounds.Height) |

### See Also

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


