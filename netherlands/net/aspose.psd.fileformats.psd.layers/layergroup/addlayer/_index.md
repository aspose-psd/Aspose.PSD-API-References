---
title: LayerGroup.AddLayer
second_title: Aspose.PSD voor .NET API-referentie
description: LayerGroup methode. Voegt de laag toe aan de lagengroep.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Voegt de laag toe aan de lagengroep.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | Layer | De laag. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u Bmp-, Jpeg-, Jpeg2000-, Png-, Psd-, Tiff-, Gif-afbeeldingen als lagen kunt toevoegen aan PsdImage

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

### Zie ook

* class [Layer](../../layer/)
* class [LayerGroup](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* montage [Aspose.PSD](../../../)


