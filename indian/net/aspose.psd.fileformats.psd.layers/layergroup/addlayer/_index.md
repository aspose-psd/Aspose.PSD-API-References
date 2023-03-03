---
title: LayerGroup.AddLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerGroup तरक. परत क परत समूह में जड़त है.
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

परत को परत समूह में जोड़ता है.

```csharp
public void AddLayer(Layer layer)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layer | Layer | परत। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि कैसे आप Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif छवियों को PsdImage में परतों के रूप में जोड़ सकते हैं

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

### यह सभी देखें

* class [Layer](../../layer/)
* class [LayerGroup](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* सभा [Aspose.PSD](../../../)


