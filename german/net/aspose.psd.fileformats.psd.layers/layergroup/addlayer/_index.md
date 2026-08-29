---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerGroup Methode. Fügt die Ebene zur Ebenengruppe hinzu."
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Fügt die Ebene der Ebenengruppe hinzu.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ebene | Ebene | Die Ebene. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie Bmp-, Jpeg-, Jpeg2000-, Png-, Psd-, Tiff- und Gif‑Bilder als Ebenen zu PsdImage hinzufügen können.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


