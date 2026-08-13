---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerGroup yöntemi. Katmanı katman grubuna ekler."
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Katmanı katman grubuna ekler.

```csharp
public void AddLayer(Layer layer)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| katman | Katman | Katman. |

## Örnekler

Aşağıdaki örnek, Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif görüntülerini PsdImage'e katman olarak nasıl ekleyebileceğinizi gösterir.

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

### Ayrıca Bakınız

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


