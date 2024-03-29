---
title: LayerGroup.AddLayer
second_title: Aspose.PSD for .NET API Reference
description: LayerGroup method. Adds the layer to the layer group
type: docs
weight: 60
url: /net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Adds the layer to the layer group.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| layer | Layer | The layer. |

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

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


