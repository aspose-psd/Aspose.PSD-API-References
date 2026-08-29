---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerGroup मेथड। लेयर को लेयर समूह में जोड़ता है"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

लेयर को लेयर समूह में जोड़ता है।

```csharp
public void AddLayer(Layer layer)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| लेयर | लेयर | लेयर। |

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif छवियों को PsdImage में लेयर्स के रूप में कैसे जोड़ सकते हैं

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

### देखें भी

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


