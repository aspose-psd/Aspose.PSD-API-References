---
title: LayerGroup.AddLayer
second_title: Referencia de API de Aspose.PSD para .NET
description: LayerGroup método. Agrega la capa al grupo de capas.
type: docs
weight: 60
url: /es/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Agrega la capa al grupo de capas.

```csharp
public void AddLayer(Layer layer)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| layer | Layer | La capa. |

### Ejemplos

El siguiente ejemplo demuestra cómo puede agregar imágenes Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif como capas a PsdImage

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

### Ver también

* class [Layer](../../layer/)
* class [LayerGroup](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* asamblea [Aspose.PSD](../../../)


