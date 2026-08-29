---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerGroup. Ajoute le calque au groupe de calques"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Ajoute le calque au groupe de calques.

```csharp
public void AddLayer(Layer layer)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| calque | Calque | Le calque. |

## Exemples

L'exemple suivant montre comment vous pouvez ajouter des images Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif en tant que calques à PsdImage

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

### Voir aussi

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


