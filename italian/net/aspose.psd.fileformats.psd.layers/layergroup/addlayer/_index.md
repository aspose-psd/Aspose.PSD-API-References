---
title: LayerGroup.AddLayer
second_title: Aspose.PSD per riferimento API .NET
description: LayerGroup metodo. Aggiunge il livello al gruppo di livelli.
type: docs
weight: 60
url: /it/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Aggiunge il livello al gruppo di livelli.

```csharp
public void AddLayer(Layer layer)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layer | Layer | Lo strato. |

### Esempi

L'esempio seguente mostra come aggiungere immagini Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif come livelli a PsdImage

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

### Guarda anche

* class [Layer](../../layer/)
* class [LayerGroup](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* assemblea [Aspose.PSD](../../../)


