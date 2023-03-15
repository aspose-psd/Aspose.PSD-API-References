---
title: LayerGroup.AddLayer
second_title: Aspose.PSD for .NET API Referansı
description: LayerGroup yöntem. Katmanı katman grubuna ekler.
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Katmanı, katman grubuna ekler.

```csharp
public void AddLayer(Layer layer)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layer | Layer | Katman. |

### Örnekler

Aşağıdaki örnek, Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif resimlerini PsdImage'a nasıl katman olarak ekleyebileceğinizi göstermektedir.

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

### Ayrıca bakınız

* class [Layer](../../layer/)
* class [LayerGroup](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* toplantı [Aspose.PSD](../../../)


