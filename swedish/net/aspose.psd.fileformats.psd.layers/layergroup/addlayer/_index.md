---
title: LayerGroup.AddLayer
second_title: Aspose.PSD för .NET API-referens
description: LayerGroup metod. Lägger till lagret i lagergruppen.
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Lägger till lagret i lagergruppen.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | Layer | Lagret. |

### Exempel

Följande exempel visar hur du kan lägga till Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif-bilder som lager till PsdImage

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

### Se även

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* hopsättning [Aspose.PSD](../../../)


