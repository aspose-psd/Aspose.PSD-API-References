---
title: LayerGroup.AddLayer
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerGroup methode. Fügt die Ebene der Ebenengruppe hinzu.
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Fügt die Ebene der Ebenengruppe hinzu.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | Layer | Die Schicht. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie Bmp-, Jpeg-, Jpeg2000-, Png-, Psd-, Tiff- und Gif-Bilder als Ebenen zu PsdImage hinzufügen können

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

### Siehe auch

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* Montage [Aspose.PSD](../../../)


