---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode LayerGroup. Menambahkan lapisan ke grup lapisan"
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Menambahkan lapisan ke grup lapisan.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lapisan | Lapisan | Lapisan. |

## Contoh

Contoh berikut menunjukkan cara Anda dapat menambahkan gambar Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif sebagai lapisan ke PsdImage

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

### Lihat Juga

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


